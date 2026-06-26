1. Run `git pull origin main` to fetch the latest changes
2. Run `cargo build --release` in `cli` folder
3. Run `npm run gulp vscode-linux-x64`
4. Copy the `code` binary from `cli/target/release` folder to `../VSCode-linux-x64/bin`
5. Rename the copied `code` binary to `code-tunnel-oss`
6. Run `npm run gulp vscode-linux-x64-prepare-deb`
7. Run `npm run gulp vscode-linux-x64-build-deb`
8. Locate the `.deb` file at inside `.build/linux/deb/amd64/deb`
