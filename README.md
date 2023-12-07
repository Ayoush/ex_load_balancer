# ex_load_balancer

`ex_load_balancer` is a simple Elixir dependency that provides a basic implementation of a load balancer. This project is designed for learning purposes, allowing you to understand key concepts in Elixir, concurrent programming, and system design.

## Implementation Overview - Point 1

### Objective

The goal of this implementation is to create a reliable service within the `ex_load_balancer` umbrella project. This service will send requests randomly and concurrently, simulating a basic load balancer functionality. The service should be fault-tolerant, automatically restarting or isolating processes in case of failures.

### Key Topics to Learn

1. **Concurrent Programming in Elixir:**
   - Learn about Elixir processes and their lightweight nature for concurrent execution.
   - Understand how to spawn and manage processes using functions like `spawn/1` and `spawn_link/1`.

2. **Supervision Trees:**
   - Explore the concept of supervision in Elixir for building fault-tolerant systems.
   - Learn about supervisors and their role in restarting child processes in case of failures.

3. **Fault Tolerance:**
   - Understand the "Let It Crash" philosophy in Elixir for achieving fault tolerance.
   - Explore trapping exits and handling exit signals.

4. **Concurrency Control:**
   - Study concurrency control mechanisms in Elixir, including locks and message passing.
   - Explore Elixir's message passing mechanism using the actor model.

5. **Random Number Generation:**
   - Implement random number generation in Elixir using the `:rand` module.

6. **Application Structure and Design:**
   - Organize the project into applications and understand their interactions.
   - Consider using an umbrella project to manage multiple related applications.

7. **GenServer:**
   - Implement the request-sending logic using the `GenServer` behavior.
   - Manage state and concurrency within the `GenServer` module.

8. **Fault Isolation:**
   - Learn about process isolation in Elixir to minimize the impact of failures.

9. **Supervisor Strategies:**
   - Choose and implement a suitable supervisor strategy, such as `:one_for_one` or `:rest_for_one`.

10. **Error Handling:**
    - Implement robust error handling in processes for graceful failure recovery.

11. **OTP (Open Telecom Platform):**
    - Familiarize yourself with OTP principles and libraries for building distributed and fault-tolerant systems.

### Getting Started

To run the `ex_load_balancer` project locally:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ex_load_balancer.git
   cd ex_load_balancer

