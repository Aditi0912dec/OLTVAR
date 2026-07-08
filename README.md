# OLTVAR
Data transformation

Privacy considerations form another central motivation for this research. 
While FL prevents direct sharing of raw visual data, it does not inherently guarantee protection
against leakage of sensitive information encoded in learned representations. 
Visual inputs, such as images and videos, often contain task-irrelevant yet sensitive content, including
identifiable individuals, background environments, and contextual cues unrelated to the
recognition task.
Existing privacy-aware visual transformation techniques often rely on uniform obfuscation or global transformations, which tend to degrade task performance by indiscriminately removing useful information. 
Conversely, insufficient masking risks exposing sensitive content indirectly through learned features. This tension drives the development
of task-aware privacy transformations that selectively suppress sensitive visual information while preserving cues essential to recognition, enabling a better privacy-utility trade-off in federated vision learning.
