# Rust setup 
## Installation 
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
- for a normal Installation Select 1: 

![img](docs/img1.png)

- After the Installation you will get this 

![img](./docs/img2.png)

- Check if everything is working by running this command 

![img](./docs/img.png)

## Running an Example 
- Create a new file called `hello.rs`, and copy the code to the file. 
```rs
fn main(){
 println!("Hello World "); 
}
```
- Compiling 
```bash
rustc hello.rs 
```
- Running 
```bash
./hello 
```

![img](./docs/img3.png)
# Resouces 
- [Youtube Plays list by Talel Hadj Salem reading the Rust book in arabic](https://youtube.com/playlist?list=PLNpnO_Q_GAdSJYAj4cwViEewEOtnpHDBb&si=Gcd8Rv36deS4h8Ag)
- [Exercises](https://github.com/rust-lang/rustlings/tree/main/exercises)
- [Rust documentation](https://doc.rust-lang.org/rust-by-example/index.html)
