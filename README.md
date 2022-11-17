# Nightly builds of cargo-shuttle so you don't have to

[Shuttle.rs](https://www.shuttle.rs/) is great, but it takes forever to build. It's especially bad in a Github Action, where you're often starting from 0 and so have to compile all 500+ dependencies from scratch just to get Shuttle up and running. Wouldn't it be great if you could just download a pre-built Shuttle binary for your OS and architecture and go from there?
