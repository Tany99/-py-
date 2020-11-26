# -py-
简单的py代码
from queue import Queue


class SegmentTreeNode(object):
class SegmentTreeNode:
    def __init__(self, start, end, val, left=None, right=None):
        self.start = start
        self.end = end
@@ -17,10 +17,10 @@ def __init__(self, start, end, val, left=None, right=None):
        self.right = right

    def __str__(self):
        return "val: %s, start: %s, end: %s" % (self.val, self.start, self.end)
        return f"val: {self.val}, start: {self.start}, end: {self.end}"


class SegmentTree(object):
class SegmentTree:
    """
    >>> import operator
    >>> num_arr = SegmentTree([2, 1, 5, 3, 4], operator.add)
