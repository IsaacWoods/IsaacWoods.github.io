---
layout: default
---

<h2># About me</h2>
Hi, I'm Isaac.

Professionally, I am a medical doctor, working in the UK, with interests in anaesthetics and critical care.

I am also an amateur software developer - my main interests are in writing a [bad operating system](https://github.com/IsaacWoods/poplar),
but I also explore embedded development, firmware, and other stuff.

I really like coffee, and have been developing my hardware and electronics knowledge by tinkering with espresso machines.
I'm hoping to write about my recent antics, adding pressure profiling and better temperature control
to a 2012 Gaggia Classic, at Some Point™.

I also enjoy travel, swimming, and SCUBA.

<hr>
<h2># Projects</h2>

- [Poplar](https://github.com/IsaacWoods/poplar) is my main project - a toy kernel and userspace written in Rust to explore design of non-UNIX operating systems.
  It doesn't do very much useful stuff yet, but I've learnt a lot over the years working on it.
- [`acpi`](https://github.com/rust-osdev/acpi) is a crate I host under the [Rust OSDev](https://github.com/rust-osdev) organisation. It is a library for interacting
  with the ACPI tables, including a fairly competent AML interpreter, written in pure Rust. It's used in Poplar, but is written as a standalone library to be used
  from other projects.

<hr>
<h2># Posts</h2>

<div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

      <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
    </article>
  {% endfor %}
</div>
