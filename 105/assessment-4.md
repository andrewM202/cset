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

The main difference between an array and an object is that an array has all its indexes pre-named, 0 to array.length-1. In an object, its keys can be named anything, as long as it is contained within quotes. This can be seen in the first and second example of code. In the first example, day1 is an object and it holds the keys squirrel and events. If I wanted to access the values inside of the day1 object, I would call either day1.squirrel or day1.events. The array contrast can be seen in the second example of code. The array journal contains two objects, and each object does not have a name. 





3. This difference leads to a slight difference in use between objects and arrays.
