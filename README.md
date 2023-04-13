# Search Algorithms

Implementation of Dijskra, A* and Tabu Search in Python to find the quickest connection between any stops in Wrocław at any given time
having real dataset from MPK Wrocław.

![Zrzut ekranu (631)](https://user-images.githubusercontent.com/100850964/231619623-f41252d1-e193-4b97-a040-974eeb03a5ac.png)

Program allows to decide if we prefer to reach destination quicker or take the lowest changes possible. Since it is an heuristic, we are looking for very good results but not necessarily the best that exists. Here is the example, criterion 't' means time and 'p' number of changes:

![Zrzut ekranu (632)](https://user-images.githubusercontent.com/100850964/231619864-6c1cc038-f7b9-4faf-a9db-074ba3d49a9b.png)

![Zrzut ekranu (634)](https://user-images.githubusercontent.com/100850964/231619868-396faab7-ab98-4ea9-bd34-73bed4829a25.png)

Finally project allows to look for the shortest path between list of stops using tabu search and implemented algorithms. I am currently working in improving this part.
