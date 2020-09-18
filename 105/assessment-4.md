1. I think I would rate myself at an 8/10 for the first course. I did a lot of things I wanted to do, like a mini side project and I spent a lot of extra time outside of class studying and looking through extra resources. However I think I could have spent some time to pre-read chapters the week before for instance. That way it is less overwhelming when new content comes. For the first three weeks, we mostly went over content I was sort of familiar with from other languages I have experience with. But this past week with the objects was pretty much all new for me, and it would have helped tremendously if I had spent time over a weekend to study the chapter in advance, which I think is also what I want to start doing for the next course. 





2. Here are the code samples from the Weresquirrel code I will be referencing: 
```
let day1 = {
  squirrel: false,
  events: ["work", "touched tree", "pizza", "running"]
};
```
```
let journal = [
  {events: ["work", "touched tree", "pizza",
            "running", "television"],
   squirrel: false},
  {events: ["work", "ice cream", "cauliflower",
            "lasagna", "touched tree", "brushed teeth"],
   squirrel: false}
   //journal extends for 90 total objects
];
```
```
function journalEvents(journal) {
  let events = [];
  for (let entry of journal) {
    for (let event of entry.events) {
      if (!events.includes(event)) {
        events.push(event);
      }
    }
  }
  return events;
}
```

The main difference between an array and an object is that an array has all its indexes pre-named, 0 to array.length-1. In an object, its keys can be named anything, as long as it is contained within quotes. This can be seen in the first and second example of code. In the first example, day1 is an object and it holds the keys squirrel and events. If I wanted to access the values inside of the day1 object, I would call either day1.squirrel or day1.events. The array contrast can be seen in the second example of code. The array journal contains two objects, and each object does not have a name. If I wanted to access the values in the journal array, I would have to call journal[0] to get its first value for instance. 





3. This difference between arrays and objects leads towards the idea that arrays are used moreso for grouping related things together, while objects are moreso for specific information on something. This can be seen in the second Weresquirrel code sample. The journal array is used to group all the objects that describe what Jacques did daily and whether or not he turned into a squirrel. The fact that all the objects are in the array make it very easy to access each element/object in the journal array. To get each object, you can simply loop through the array using a for of loop. This is seen in the journalEvents function which is the third code sample, which gets the value inside each object with just two nested for loops. If it was arrays inside one big object, it would not be as simple as using a for loop or two. Each of the keys in the object would have a different name, and recursion or calling each individual key out would have to be done, which is much more complex that doing something similar to the journalEvents function. This ease of accessing values for arrays is why the objects are inside of the array instead of the vice versa for the journal array, which is the second code sample.
  As far as how I could have used arrays and objects in my adventure game, there are multiple ways. I could have had the player's stats, the player's weapons, as well as any mobs and their hps stored inside of separate objects. I can then store all of these objects inside of a gameElements array. If I want to access a goblin's hp and attack stat, I can call any of the values of an object inside of the array inside any of the scenes I created very simply. All of the stats or mobs I want to track throughout the game are all stored in one place as well. And if I want to dublicate a mob and create a replica goblin for another scene, I can simply use the Object.assign method. Since the objects are stored inside of an array, if I want to print out the stats of a given mob, it would be simple to print out everything using a similar setup to the journalEvents function in my third Weresquirrel example. 
  
