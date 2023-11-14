# Qcynaut App

Qcynaut app intended to provide comfort to clients, and the client can be more easy to track their progress.

## Features

- Progress tracking
- Open issue
- Demo
- Source code inspection
- In App chat
- In App meeting
- Blogs
- Portfolio
- Submit Project

## Motivation

By using this app, It's eliminate the needs of sharing github repositories and lot of question about progress of the project, also give the more detailed explanation about the project more ease.

By creating this app, it provides simplicity to scale from personal into teams.

## Tech consideration

Here are few tech that's will be used.

#### SvelteKit

It is good for the website speed, because sveltekit was helpful for handling user interaction and handling server side requests.

#### Rust

Since rust by default over memory-safe guarantee and useful for concurent programming, It might be good to use this language, also because the server will handle much complex operation that interact with low level system interface, it such a nice choice to have rust in line.

#### WebAssembly

Well as we know that the web interface will be interactive and feature full, instead of writing JS/TS code to interact with the `rust` code, we will transform the `rust` code into webassembly to cut down the development time.

#### Redis

To make such complex structure become fast to access we need caching, that why redis come in mind.

#### MongoDB

The structure of the data will be more complex and lot of custom labeling, so MongoDB is the best choice for this.

#### GraphQL

To give more abstraction when we run some query, it is the best option instead of using REST.

#### Kotlin

For the Android app kotlin will be come first so the app will be specialized for the platform it self, and maybe if I consider to create iPhone app it will be using swift.

#### Core Libraries

It still needs some research for this.