# ALGORITHMS FOR COVERING BARRIER POINTS BY MOBILE SENSORS WITH LINE CONSTRAINT 
In this thesis, we develop efficient algorithms for the problem of covering barrier points
by mobile sensors. Each sensor is represented by a point in the plane with the same covering
range r so that any point within distance r from the sensor can be covered by the sensor.
Given a set B of m points (called \barrier points") and a set S of n points (representing
the \sensors") in the plane, the problem is to move the sensors so that each barrier point
is covered by at least one sensor and the maximum movement of all sensors is minimized.
The problem is NP-hard. In this thesis, we consider two line-constrained variations of
the problem and present effcient algorithms that improve the previous work. In the first
problem, all sensors are given on a line L and are required to move on L only while the barrier
points can be anywhere in the plane. We propose an O((n+m) log(n+m)) time algorithm
for the problem. We also consider the weighted case where each sensor has a weight; we
give an O((m + n) log2(m + n)) time algorithm for this case. In the second problem, all
barrier points are on L while all sensors are in the plane but are required to move to L to
cover all barrier points. We solve the weighted case in O(mlogm + n log2 n) time.
