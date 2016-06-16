# StatLib [![Release](https://jitpack.io/v/mayojava/statlib.svg)](https://jitpack.io/#mayojava/Repo)
Statistics library for Android

# Download
Add it in your root `build.gradle` at the end of repositories:

```
allprojects {
	repositories {
		...
		maven { url "https://jitpack.io" }
	}
}
```
Add the dependency to your add module `build.gradle` file:

```
dependencies {
	compile 'com.github.mayojava:statlib:v1.0'
}

```
# Usage
To compute the Arithmetic mean of a set of numbers for example,

```
//create the list of numbers
ArrayList<Integer> numbers = new ArrayList<>();
numbers.add(10);
numbers.add(12);
numbers.add(5);
numbers.add(9);
numbers.add(16);
numbers.add(4);

//call the static arithmeticMean method from the CentralTendency class
double mean = CentralTendency.arithmeticMean(numbers).doubleValue();

```

# License
```
Copyright 2016 Mayowa Adegeye

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```