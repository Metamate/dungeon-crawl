# dungeon-crawl

to build for web:
cargo build --target wasm32-unknown-unknown --release --features=opengl
wasm-bindgen .\target\wasm32-unknown-unknown\release\dungeon_crawl.wasm --out-dir ./pkg/ --no-modules --no-typescript
