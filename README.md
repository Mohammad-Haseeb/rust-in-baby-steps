# rust-in-baby-steps
for package managment we're using cargo tool 
we'll build project starter's using cargo
 ## cargo common commands
 ```
  cargo new hello_carge
  cargo build
  cargo run  
  cargo check
  cargo build --release 

 ``` 
 # Varaibles
  1. We can't use value of other variable in const except const type variable
  2. We can't reshadow  const
  3. by default variable are immutable but we can make mutable with help of ### mut keyword
  4. With out mut we cant re-assign value to variable and but we can reshadow varaible with let keyword like making new variable.

## reshadow
```
fn main() {
    let x = 5;

    let x = x + 1;

    {
        let x = x * 2;
        println!("The value of x in the inner scope is: {x}");
    }

    println!("The value of x is: {x}");
}
```