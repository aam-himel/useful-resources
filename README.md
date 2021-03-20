# Easy to access some of the concepts for problem solving.

### Commonly used STL Container and Functions

#### 1. Key value pair with vector

```c++
vector< pair<int, string> > v;
v.push_back(make_pair(1, "himel"));
cout << v[0].first << endl << v[0].second << endl;
```

#### 2. Max element from an Vector using - max_element(nums.begin(), nums.end())

```c++
vector<int> nums = {12, 4, 32, 56, 1};
auto it = *max_element(nums.begin(), nums.end());
cout << it;
```
