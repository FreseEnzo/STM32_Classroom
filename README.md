# STM32 Classroom

## Overview
Welcome to the STM32 RoboIME Classroom repository! This repository is your go-to resource for mastering techniques with STM32 microcontrollers. Each class in this series delves into specific debugging methodologies, equipping you with the skills needed to troubleshoot and optimize your STM32 projects effectively.

## Classes

1. **Class 1: Debugging with CDC**
   - Learn the fundamentals of debugging using CDC (Communication Device Class).
   - Setup and configure CDC for debugging STM32 applications.
   - Implement basic debugging scenarios leveraging CDC.

2. **Introduction to Real-Time Operating Systems (RTOS)**
   - Understand the fundamentals of RTOS.
   - Learn about the advantages of using an RTOS in embedded systems.

3. **Overview of FreeRTOS**
   - Explore the features and architecture of FreeRTOS.
   - Understand the concepts of tasks, queues, semaphores, and other synchronization primitives in FreeRTOS.

4. **Task Management**
   - Learn how to create, manage, and prioritize tasks in FreeRTOS.
   - Understand task synchronization and communication mechanisms.

5. **Memory Management**
   - Explore memory management strategies in FreeRTOS.
   - Learn about dynamic memory allocation and memory protection.

6. **Interrupt Handling**
   - Understand interrupt handling in FreeRTOS.
   - Learn how to configure and manage interrupts within the FreeRTOS framework.

7. **Resource Management**
   - Explore techniques for managing shared resources in FreeRTOS.
   - Learn about mutexes, binary semaphores, and other resource synchronization mechanisms.

8. **Real-Time Scheduling**
   - Understand the scheduling algorithms used in FreeRTOS.
   - Learn how to configure task scheduling policies and priorities.

9. **Advanced Features**
   - Explore advanced features and capabilities of FreeRTOS.
   - Learn about software timers, event groups, and task notifications.

## Resources

- **Code Samples**: Each class provides code samples and projects for hands-on learning.
- **Documentation**: Detailed documentation and guides accompany each class to aid understanding and implementation.
- **Community Support**: Engage with peers and instructors in the community forum for questions, discussions, and collaboration.

## How to Use This Repository

1. **Clone the Repository**: Clone or download this repository to your local machine.
2. **Explore Class Directories**: Navigate to the class directories to access relevant materials for each session.
3. **Follow Along**: Follow the provided instructions in each class directory to participate in activities and exercises.
4. **Contribute**: Share your insights, improvements, or suggestions by submitting pull requests or opening issues.

## Feedback

Your feedback is crucial for enhancing the content and direction of this repository. If you have any suggestions, questions, or concerns, please reach out.

Get ready to elevate your STM32 debugging skills with our comprehensive series! 🛠️

## Trainees Area
### Task 1 (Know-how FreeRTOS works)

**Trainee:** [Favalessa](https://github.com/dekera)
**Date:** 18/05/2024
**Resume:** Being a class of the RTOS the FreeRTOS is small enough to run on a microcontroller and provides certain functionalities such as inter-task communication, real time scheduling functionality, timing and synchronisation primitives for the core. With those functionalities it's possible to decide which program to run and when specifying that the embedded system must respond to a certain event within a deadline(certain strictly defined time). In particular, the FreeRTOS scheduler achieve the execution pattern by allowing the user choose the priority to each thread of execution. Thus, it's very important and effective when we need to do simultaneously tasks that needs to be classified with priorities.

**Trainee:** [Galvão](https://github.com/edugalvao021)
**Date:** 18/05/2024
**Resume:** FreeRTOS é um tipo de sistema operacional em tempo real, ou seja, um tipo de RTOS. Alguns dos principais recursos encontrados nele são: tarefas(uma função em C; unidade básica de execução), filas(comunicação entre tarefas), semáforos e mutexes(utilizados para sincronização entre tarefas) e temporizadores(executa funções após um tempo definido). Basicamente, ele garante que atividades sejam realizadas dentro de prazos, o que demonstra que esse tipo de sistema operacional é bastante adequado a sistemas embarcados onde o tempo de resposta é sensível, isto é, crítico. Um exemplo que considero interessante, é o fato de conseguir interromper tarefas que estejam em execução para dar prioridade a outras que tenham um prazo menor ou que tem maior prioridade. Vale ressaltar, ainda, que FreeRTOS é um RTOS utilizado em microcontroladores (no nosso caso, utilizado na família de microcontroladores STM32). Outro ponto válido, é a execução de tarefas de maneira simultânea e otimizando o gerenciamento de tais tarefas na forma a evitar o desperdício de ciclos de CPU, ou seja, sempre prezando no uso controlado e eficaz de recursos do sistema. Tal efeito garante a boa funcionalidade do próprio sistema embarcado com recursos limitados. Ademais, ainda ressaltando o fato da alta precisão, temos os temporizadores com alta eficácia, pois assim não garantiríamos a alta precisão na execução das tarefas a serem realizadas. 