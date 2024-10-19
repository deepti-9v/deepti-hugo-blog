---
title: "Simple Blog Post 1"
date: 2018-09-12T12:52:36+06:00
image_webp: images/blog/blog-post-3.webp
image: images/blog/blog-post-3.jpg
author: John Doe
description : "This is meta description"
---

## Syntax Cheat Sheet:


## HashSet
```csharp {linenos=true}
    HashSet<int> set = new HashSet<int>();
    foreach(var i in nums){
        if (!set.Contains(i)){
            Console.WriteLine("not contains");
            set.Add(i);
        }
        else {
            return true;
        }
    }
```

## Dictionary
```csharp {linenos=true}
    Dictionary<char, int> mapping = new Dictionary<char, int>();

    foreach(var c in s){
        if (!mapping.ContainsKey(c)){
            mapping.Add(c, 1);
        }
        else{
            mapping[c] += 1;
        }
    }

    foreach(KeyValuePair<char, int> entry in mapping){
            Console.WriteLine($"char {entry.Key} count {entry.Value}")
    }
```

## Array
```csharp
   int array[] = new int[];
   Array.Clear(array);
   Array.Clear(array, 0, array.Length);
```



## Convert Dictionary to Array

```csharp {linenos=true}
    Dictionary<string, List<string>> map = new Dictionary<string, List<string>>();
    map.Values.ToList<List<string>>(); //Its a list of List<string>
```

## Priority queue
```csharp {linenos=true}
var heap = new PriorityQueue<int, int>();
heap.Enqueue(1,2);
heap.Dequeue();
```



Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae. Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.

Sed porttitor lectus nibh. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Nulla porttitor accumsan tincidunt. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Quisque velit nisi, pretium ut lacinia in, elementum id enim.

> Design is not just what it looks like and feels like. Design is how it works.

Praesent sapien massa, convallis a pellentesque nec, egestas non nisi. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a.

Sed porttitor lectus nibh. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Donec velit neque, auctor sit amet aliquam vel, ullamcorper sit amet ligula. Vestibulum ac diam sit amet quam vehicula elementum sed sit amet dui. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus magna justo, lacinia eget consectetur sed, convallis at tellus. Nulla porttitor accumsan tincidunt. Mauris blandit aliquet elit, eget tincidunt nibh pulvinar a. Curabitur arcu erat, accumsan id imperdiet et, porttitor at sem. Quisque velit nisi, pretium ut lacinia in, elementum id enim.