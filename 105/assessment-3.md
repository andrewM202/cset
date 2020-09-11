1. So far, I feel that the pace of the program is just right for me. I do acknowledge that I have the benefit of knowing a prior programming language, 
and I feel this gives me the benefit of more "wiggle room" to learn concepts and the "why" of how everything works much more. I am learning the syntax and 
style rules of JavaScript easily enough, and so I have enough time to look through all the extra resources, build fun projects on the side, and explore the 
language much more in depth (like understanding how various things are stored in memory) than otherwise. Perhaps that might change as we go into harder topics, 
but for now I feel the pace is just right.  

2. Functions are so useful because of the organization it brings to the program, and because they reduce large chunks of repetitive code to a single call 
to a function. In the case of reducing long repetitive code, I may write a program where I have to perform a specific set of mathematical steps on a bunch 
of numbers. Rather than write out the mathematical calculations anew for each number, I can just send each number into the function whenever necessary. 
Rather than write the same calculations a hundred times, I only have to write it out once and send the numbers in. As for organization, reading code that 
uses functions looks a lot less messy than code that doesn't use them. I can scroll through and see, "Oh, here is the function to calculate the best outcome, 
and here is the function to calculate interest" and also see that each function has a name to see its purpose. Meanwhile, if you have to type out the entire set 
of calculations every time, your code would look bulky and unwieldly than it would otherwise. I would also have to read all that bulky code to see what interest, 
for instance, you are specifcally counting, whereas a call to a function might have the percent interest laid out right in the arguments.

3. A zoo can be used as a great analogy for scope. But first, here is the code I will be referencing:
```
let zookeeper;
const aquaticBuilding = function() {
  if(zookeeper)
  //no error thrown for using zookeeper or aquaticTreatment in if statement
  
  let aquaticTreatment;
  if(aquaticTreatment === true) {
    let alligator;
    
    //no error thrown for using zookeeper, aquaticTreatment, or alligator
    if(zookeeper);
    if(aquaticTreatment);
    if(alligator);
  }
}
if(aquaticTreatment)
//error
```
Then to start off with the analogy, the zookeeper represents the global scope, because he can be anywhere in the zoo: any exhibit, 
and animal pen, all in order to take care of the animals. For a JavaScript example, imagine the `zookeeper` variable. It can be accessed in the aquaticBuilding 
function as well as inside the if statement in the function. Now, the specific exhibit, for instance the aquatic exhibit, represents a local scope. Only aquatic 
animals can be accessed/found inside the aquatic building, the same way local variables can only be accessed inside their function or block, and not from anything 
outside of it. In the JavaScript example, this is the same as the `aquaticTreatment` variable: the if statement in the function can access it, but accessed outside
of the function an error is thrown. Next, imagine each individual 
pen inside of the exhibit, like one for alligators and one for dolphins. These pens are like nested scopes. They are inside of the aquatic building, and get 
access to all the treatment an animal in the aquatic building would get, like access to water and fish food in the pens. Each aquatic animal gets access to the
aquatic building's treatment, as well as access to the zookeeper to feed them. This is akin to how a nested function can access the variables of the function
holding it, and the same way the nested function can also access global variables. In the JavaScript example, the `alligator`, `aquaticTreatment`, and `zookeeper` can all
be accessed with no errors. Finally, there is lexical and block scoping. In the JavaScript code, the if statement with the `aquaticTreatment` variable as its conditional
in the function creates a local scope, and the aquaticBuilding function creates a local scope. The function's scope is lexical scoping, and the if statement's 
scope is block scope because it is not a function and uses curly brackets. In the zoo analogy, this is like the different animal buildings: one for birds
and one for aquatic animals. They both have their own scopes, they are just defined differently from each other. 

