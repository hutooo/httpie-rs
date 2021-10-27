# httpie-rs
reimplement HTTPie via Rust

```sh
cargo fmt  # 格式化代码
cargo clean  # 清理 target文件
cargo build [--quiet]  # 编译代码
cargo test  # 测试

# 运行测试
cargo run post https://httpbin.org/post greeting=hola name=ash
# ./target/debug/httpie post https://httpbin.org/post greeting=hola name=ash
```
