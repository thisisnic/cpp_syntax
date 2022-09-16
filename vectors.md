Unlike arrays, vectors are dynamic, i.e. can be resized.

# Create a vector

## Declare a vector without supplying values

```
vector<int> numbers(3);
```

## Declare a vector and supply its values

```
vector<int> numbers{44, 55, 66};
```
  
# Print value at index
 
```
cout << numbers.at(0) << endl;
```
If the index doesn't exist, you'll get an error.

# Vector size

```
cout << numbers.size() << endl;
```

# Add elements

## Append element to vector

```
numbers.push_back(42);
```

## Add element at specific location

You can use `.begin()` to use 1-based indexing.

```
numbers.insert(numbers.begin()+1, 42);
```

# Remove elements

## Remove last element

```
numbers.pop_back();
```

## Remove first element

```
numbers.erase(numbers.begin());
```

# Modify elements

```
numbers.at(1) = 3;
```

# Iterate through vector

## Basic

```
for(int i = 0; i < numbers.size(); i++){
  cout << numbers.at(i) << endl;
}
```

## Fancy pants


```
for(auto i: numbers){
  cout << i << endl;
}
```
