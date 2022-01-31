
# Master Ventures Rust Test!
![](https://i.ibb.co/DMFTFxk/Screen-Shot-2021-12-21-at-2-25-04-PM.png)

## Introduction

Thank you for taking the time to interview with us here at Master Ventures! First things first, we here at Master Ventures understand that writing code which is simple in other languages may be very challenging initially in Rust. 

This test is meant to demonstrate to us how you organize code, what are your strategies when writing Rust code, as well as standard performance and optimization trade-offs. We want to see how you express yourself through code so just be you! 

There will be many solutions to the problem we just want to see you pick an approach and do it well! Algorithm performance is not everything here. All that being said, what is most important is that your work is yours. If you have to look something up feel free to do so but make sure to understand what you are doing. We will ask you to explain your solution thoroughly!

## Problem

### LRU Cache

Caches serve an important optimization purpose in accessing a relatively small set of memory quickly. What separates various caches from one another is their respective eviction policy. LRU Caches work off the principal of Least Recently Used i.e. recently used repetitious data accesses to a particular set of data is optimized! 

Wikipedia has a great short description of LRU Caches found [here](https://en.wikipedia.org/wiki/Cache_replacement_policies#Least_recently_used_(LRU))

## Requirements

1.) Your implementation of the LRU cache should be in a rust library format.

2.) Your code should include tests for verification (**Hint**: This is highly valued here!)

3.) Only the ```std``` crate should be used for this implementation. (If there are other outside crates they are worthy of discussion but not to be used in this implementation)

4.) Runtime and Space complexity should be provided. This does **NOT NEED** to be optimal.(**Hint**: the optimal solution in Rust for this problem is NOT trivial we are not expecting it! Though if you are able to don't let us stop you!) We want to see that you can identify the speed/space limitations of your program.

5.) Your cache should be generic. i.e. keys and values can be of varying types such as: ```i32```, ```f32```, ```String``` etc. (Do not worry too much about collection slices for this.)

6.) Your LRU Cache should implement the following operations:

```rust
@return Cache
fn new(capacity) // Should create a cache with the given capacity
```
```rust
@return Optional
fn put(key, value) // For a given key place the following value inside the cache
```
```rust
@return Value
fn get(key) // For the given key return corresponding value in the cache
```

## Deliverables
zip your src and cargo package and ask your Master Ventures contact for information on where to send it.

## Questions

Any questions or concerns please reach out to your Master Ventures contact and we will respond immediately. Do not be afraid to ask! Any questions are welcome!

# Conclusion

Thank you again for your time we look forward to working with you!!

![](https://i.ibb.co/fFp2nq3/Screen-Shot-2021-12-21-at-3-01-06-PM.png)
