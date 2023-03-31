# About flatten synthesis vs nonflatten synthesis

<p align="justify">In VLSI design, the terms "flatten synthesis" and "non-flatten synthesis" refer to different approaches for integrating the design hierarchy during the synthesis process.</p>

<p align="justify">Flatten synthesis is a technique where the hierarchical structure of the design is removed, and all modules are flattened into a single module. In this approach, all sub-modules are merged with their parent module, and the resulting design has no hierarchy. This approach simplifies the design and can result in a more efficient implementation in terms of area and timing.</p>

<p align="justify">On the other hand, non-flatten synthesis is a technique where the hierarchical structure of the design is preserved during synthesis. In this approach, sub-modules are synthesized separately and then integrated into the parent module. This approach allows for easier verification and debugging of the design since the hierarchy reflects the original design. However, it can also result in a larger design and longer synthesis times.</p>

<p align="justify">In summary, flatten synthesis sacrifices design hierarchy for efficiency, while non-flatten synthesis prioritizes design hierarchy for easier verification and debugging. The choice between the two approaches depends on the specific requirements and constraints of the design project.</p>
