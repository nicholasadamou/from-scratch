# 🌱 From Scratch

![from-scratch](https://socialify.git.ci/nicholasadamou/from-scratch/image?description=1&name=1&owner=1&pattern=Circuit+Board&theme=Light)

A collection of simplified implementations of complex systems, built from scratch to understand their core principles.

## Overview

The _"from scratch"_ principle is a learning approach where you take a complex system (like Redis, Nginx, or Docker) and build a simplified version to understand its fundamental concepts. By stripping away advanced features and focusing on core functionality, you gain deep insights into how these systems actually work.

## Why Build From Scratch?

- **Deep Understanding**: Building something from scratch forces you to understand every component and design decision
- **Learning Best Practices**: You discover why certain patterns and architectures are used
- **Demystification**: Complex systems become less intimidating when you build a basic version yourself
- **Better Debugging**: Understanding the fundamentals helps you troubleshoot real systems more effectively

## Projects

### [Load Balancer](https://github.com/nicholasadamou/spring-boot-load-balancer-demo)

![Spring](https://img.shields.io/badge/-Spring-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=Docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

A simplified load balancer implementation in Java using Spring Boot that demonstrates:

- Round-robin load distribution
- Health checking
- Service discovery
- Request proxying
- Docker containerization

You can read an article about this project [here](https://www.nicholasadamou.com/notes/building-a-simple-load-balancer-with-spring-boot).

### [Data Structures](https://github.com/nicholasadamou/databricks)

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pytest](https://img.shields.io/badge/-Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)

A collection of data structures that are not included in the Python standard library built to learn more about data structures and algorithms.

I wrote an article on [_A Deeper Than Not Dive Into Two Sum_](https://www.nicholasadamou.com/notes/a-deeper-than-not-dive-into-two-sum), exploring the infamous LeetCode problem #1, [Two Sum](https://leetcode.com/problems/two-sum). In this article, I explained my thought process behind databricks and why building systems _from scratch_ is a useful learning technique for the curious developer. Moreover, I take a deep dive into the low level design of a hash map that features the [Hash Map](https://github.com/nicholasadamou/databricks/tree/master/HashMap) implementation from databricks. You can read this section of the article [here](https://www.nicholasadamou.com/notes/a-deeper-than-not-dive-into-two-sum#before-we-begin).

## Development Guidelines

When building _"from scratch"_ implementations:

1. **Start Small**: Begin with the absolute minimum feature set
2. **Focus on Core Concepts**: Implement fundamental features first
3. **Keep It Simple**: Avoid premature optimization
4. **Document Everything**: Explain key concepts and design decisions using diagrams like [plantuml](https://plantuml.com) or [mermaid](https://mermaid.js.org).
5. **Include Tests**: Demonstrate how the system should work
6. **Use Modern Tools**: Leverage current languages and frameworks

## Resources

Helpful resources for building systems from scratch:

- [Build Your Own X](https://github.com/danistefanovic/build-your-own-x)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
