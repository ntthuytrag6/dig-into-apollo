# Dig into Apollo ![GitHub](https://img.shields.io/github/license/daohu527/Dig-into-Apollo.svg?style=popout) [![Documentation Status](https://readthedocs.org/projects/dig-into-apollo/badge/?version=latest)](https://dig-into-apollo.readthedocs.io/en/latest/?badge=latest)

> **"Shifting from Code Analysis to Engineering Wisdom."**.

Dig into Apollo was originally designed to help developers navigate the [Apollo](https://github.com/ApolloAuto/apollo) autopilot system. As AI evolves to handle basic code explanation, this project is pivoting to focus on **Design Patterns**, **Engineering Trade-offs**, and **Real-world Troubleshooting**—the "human" experience that AI cannot replicate.

---

## Founder's Note: A New Chapter

I am currently building **[WheelOS](https://github.com/wheelos)**—an autonomous driving system driven by user input. While startup life is demanding, it provides a unique vantage point on what truly matters in production.

I am rededicating my efforts here to share high-value insights: moving beyond "how the code reads" to **"how the system is designed and why it fails."** Expect future updates to focus on problem-solving frameworks and architectural evolution.

---

## New Horizon: Design & Experience

The future of this project lies in these high-level engineering domains:

* **[Engineering Philosophy (PEPs)]()**: Establishing "Apollo Enhancement Proposals"—design standards and best practices for AD.
* **[Problem Diagnosis]()**: Post-mortems of system failures and strategies for millisecond-level latency optimization.
* **[Architectural Trade-offs]()**: Analyzing why specific algorithms were chosen over others in real-world constraints.

---

## 📂 Table of Contents

### 🏛️ Legacy: Deep Dive Archive (Classic Code Analysis)

*The following sections contain detailed, line-by-line code analysis. While valuable for understanding the foundation, please refer to the "New Horizon" sections above for modern engineering insights.*

- [What's apollo](what_is_apollo)
- [How to build](how_to_build)
- [Code learning](code_learning)
    - [cyber](cyber)
    - [docker](docker)
    - [modules](modules)
        - [audio](modules/audio)
        - [bridge](modules/bridge)
        - [canbus](modules/canbus)
        - [data](modules/data)
        - [drivers](modules/drivers)
        - [dreamview](modules/dreamview)
        - [map](modules/map)
        - [localization](modules/localization)
        - [perception](modules/perception)
        - [prediction](modules/prediction)
        - [routing](modules/routing)
        - [planning](modules/planning)
        - [control](modules/control)
        - [transform](modules/transform)
        - [tools](modules/tools)
        - [v2x](modules/v2x)
- [performance](performance)
- [simulation](simulation)
- [library](library)
- [papers](papers)
- [questions](questions)

---

## 🛠 Getting Started

1. **Macro Understanding**: Grasp module functions first. It’s hard to understand the code if you don’t understand the intent. See this [Beginner Tutorial](https://apollo.auto/devcenter/coursetable_cn.html?target=1).
2. **Learn by Modules**: Follow the specific documentation within this project to see how theories are implemented in code.
3. **The "Pain Zone"**: Learning Apollo is difficult. Stay persistent; it usually takes 1-2 months of consistent study to feel comfortable.
4. **Practice & Improve**: No system is perfect. Try to implement latest https://www.google.com/search?q=papers, modify configurations, and "make your hands dirty" in the simulator.

---

## 📖 Recommended Resources

* **C++ Foundations**: I recommend **"C++ Primer"** or courses by [Hou Jie](https://search.bilibili.com/all?keyword=%E4%BE%AF%E6%8D%B7).
* **Simulation**: Use [LGSVL](https://github.com/lgsvl/simulator).
* **Theoretical Depth**: [Hongyi Li's Deep Learning](https://www.bilibili.com/video/BV1JE411g7XF?p=1) and [3Blue1Brown's Math](https://space.bilibili.com/88461692/).

---

## 🤝 Contributing

Contributions that focus on design patterns, bug-fixing experiences, or architectural improvements are highly welcome.

## 🔗 References

* [Apollo Official](https://github.com/ApolloAuto/apollo)
* [Awesome Self-Driving Car](https://github.com/daohu527/awesome-self-driving-car)
