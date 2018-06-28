---
layout: page
title: About
permalink: /about/
---

I'm a 17 year-old student from the UK, interested in low-level programming, especially in Rust.

### OS Development
My main project is [Pebble](https://github.com/IsaacWoods/pebble), which is still in its very early stages. Pebble is a microkernel that has ditched system calls in favour of message passing. Similar to how
UNIX models everything as a file, everything in Pebble is a 'node', an object that can send and receive messages. Rust's strong type system allows us to enforce the safe handling of these messages. While the
kernel is nowhere near even a working prototype, I'm excited to see how it turns out.

I'm also a member of the [Rust OSDev](https://github.com/rust-osdev) organisation, where I host the [`acpi`](https://github.com/rust-osdev/acpi) library, and also contribute to some other projects.

### Teensy keyboard firmware
My side project at the moment is [teensy-kbd](https://github.com/IsaacWoods/teensy_kbd), a firmware for mechanical keyboards using the Teensy 3.2. It's also written in Rust, and is not yet very functional.

### Programming languages
I also dabble in programming language and type theory. My largest project has been [Roo](https://github.com/IsaacWoods/Roo), a compiler for a small programming language similar to Rust, written in C++.
