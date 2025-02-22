# 沙滩占位博弈模型研究

## 项目概述
本项目是XMU短学期课程《博弈论》课程论文——关于博弈论在沙滩占位模型中的应用研究。项目探讨了在不同顾客分布假设下，多个小贩如何通过选择位置来最大化顾客数量，并分析了不同场景下的纳什均衡策略。

## 项目背景
沙滩占位模型由社会学家霍特林于1929年首次提出，用于描述商家在有限空间内的选址竞争行为。该模型假设顾客会选择离自己最近的小贩购买商品，从而引发小贩之间的战略互动。这一模型广泛应用于经济学、城市规划和政治学等领域，帮助理解竞争者在有限市场中的策略调整和均衡状态。

## 研究问题与方法
### 研究问题
1. **两人博弈场景**：在顾客均匀分布的情况下，两个小贩的纳什均衡位置是什么？
2. **一般分布情况**：在非均匀分布的顾客情况下，均衡策略如何变化？
3. **多人博弈场景**：当参与者超过两人时，均衡策略是什么？特别是三人、四人及更多参与者的情况。

### 研究方法
- **数学建模**：通过博弈论的概念，建立效用函数和最优反应函数。
- **理论推导**：通过数学分析，推导不同场景下的纳什均衡。
- **图形化展示**：通过图表展示最优反应函数和均衡点。

## 研究结论
1. **两人博弈场景**：纳什均衡是唯一且稳定的，两个小贩最终会选择位于沙滩的中点（0.5）。
2. **一般分布情况**：均衡点会移动到顾客分布的中位数位置，且均衡唯一。
3. **多人博弈场景**：
   - **三人博弈**：不存在稳定的纳什均衡。
   - **四人及以上博弈**：会出现稳定的均衡策略，小贩会以成对或对称的方式分布在沙滩上。例如，四个小贩会选择位于（0.25, 0.25, 0.75, 0.75）。

## 引用

- Hotelling, H. (1929). Stability in Competition. *Economic Journal*.

欲了解更多详情，请参阅 [博弈论课程论文](./博弈论课程论文.pdf)

--- 

# Beach Location Game Theory Project

## Project Overview
This repository contains a course project on Game Theory, focusing on the application of strategic positioning in the Beach Vendor Location Model. The project explores the Nash equilibria of vendors' locations under various customer distribution assumptions and different numbers of players.

## Project Background
The Beach Vendor Location Model, initially proposed by Hotelling in 1929, is a classic example in Game Theory that describes the strategic interaction between vendors choosing locations to maximize their customer base. This model is widely applicable in economics, urban planning, and political science, providing insights into how competitors adjust their strategies in a limited market space.

## Research Questions and Methods
### Research Questions
1. **Two-Vendor Scenario**: What are the Nash equilibria when two vendors compete on a beach with uniformly distributed customers?
2. **General Customer Distributions**: How do the equilibrium strategies change under non-uniform customer distributions?
3. **Multi-Vendor Scenarios**: What are the equilibrium strategies when more than two vendors are involved? Specifically, how do the strategies differ for 3, 4, and more vendors?

### Methods
- **Mathematical Modeling**: Formulating the problem using Game Theory concepts, including utility functions and optimal response functions.
- **Analytical Derivation**: Deriving Nash equilibria through mathematical analysis for different scenarios (uniform vs. general distributions, two vs. multiple vendors).
- **Graphical Illustrations**: Using diagrams to visualize the optimal response functions and equilibrium points.

## Conclusions
1. **Two-Vendor Scenario**: The Nash equilibrium is unique and stable, with both vendors locating at the center (0.5) of the beach.
2. **General Distributions**: The equilibrium point shifts to the median of the customer distribution, maintaining uniqueness.
3. **Multi-Vendor Scenarios**:
   - **Three Vendors**: No stable Nash equilibrium exists.
   - **Four or More Vendors**: Stable equilibria emerge, with vendors clustering in pairs or symmetrically distributed across the beach. For example, four vendors locate at (0.25, 0.25, 0.75, 0.75).


## References

- Hotelling, H. (1929). Stability in Competition. *Economic Journal*.


## Acknowledgements
This project was completed as part of a course in Game Theory at XMU. Special thanks to the course instructor and peers for their guidance and support.



For more details, please refer to the full project report in the [Game theory course paper](./博弈论课程论文.pdf) 
