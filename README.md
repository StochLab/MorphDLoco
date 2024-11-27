# MorphDLoco: Morphology aware Diffusion policy for multi-robot multi-skill locomotion

Learning from offline datasets poses scalability
challenges for robotics due to their limited availability. Fur-
thermore, current offline learning techniques in robotics either
lack the ability to translate effectively to real-time deployment
or fail to capture the inherent diversity within the datasets.
In this work, we propose a diffusion learning framework as a
unified policy capable of distilling multiple skills across a variety
of robotic platforms into a single architecture. We leverage dif-
fusion’s multimodal capabilities to learn from diverse datasets,
demonstrating that our single diffusion-based policy can learn
multiple locomotion gaits—such as trot, pronk, bound, and
pacing—across quadrupedal robots with varying morphologies
and physical parameters. An emergent advantage of our method
is its ability to transfer learned skills to a robot with a
new morphology in a zero-shot manner.
