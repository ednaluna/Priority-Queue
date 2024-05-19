# Priority Queue

This repository contains the implementation of a Priority Queue in C++. 

## Functions & Features 
Push and Pop functions insert and remove elements based on their priority with the current array.
Supports different types of data anc custom comparators. 

## Example:
PriorityQueue<int> pq;
pq.push(10);
pq.push(5);
pq.push(20);
while (!pq.empty()) {
    std::cout << pq.top() << " ";
    pq.pop();
}
