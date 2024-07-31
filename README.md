# The Priority Queue Abstract Data Type
This is a collection of prioritized elements that allows arbitrary element insertion,
and allows the removal of the element that has first priority. When an element is
added to a priority queue, the user designates its priority by providing an associated
key. The element with the minimum key will be the next to be removed from the
queue (thus, an element with key 1 will be given priority over an element with
key 2).

## PriorityQueueBase class
It's an abstract base class for a priority queue.

## HeapPriorityQueue
A min-oriented priority queue implemented with a binary heap.