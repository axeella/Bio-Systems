### Which mutation is most dangerous and why? Provide quantitative evidence.

The most dangerous mutation appears to be the p53 knock out. Because of the loss of tumor suppression, all starting states within the boolean model will lead to growth. According to the analysis of all possible starting states, 50% of those will be normal growth, while the other 50% will be tumor-like growth. This is usually dangerous for the organism. The MYC amplification presents similar consequences, and is thus also dangerous. This is because MYC will cause the knock out of p53, practically.

### Explain the role of feedback loops (e.g., MYC -> MDM2 -> p53)

Practically, feedback loops such as this one are used to regulate the growth of the cell. P53 prevents the cell from growing too much, by stoping the growth at specific points but also causing the cell's death when DNA is damaged. It produces MDM2 to self-regulate. MYC also creates MDM2, which allows for phases of greater growth, with the possibility of fine tuning the amount of p53 present at any point in the cell, and therefore control its growth. These feedback looks can however be hijacked in unusual circumstances, such as MYC abundance. This will cause MDM2 to be overproduced, which will functionally knock out p53. In that case, if the DNA happens to be damaged, the absence of p53 will prevent the cell from dying out, and it will simply grow, potentially in a tumor-like manner.

### What are the limitations of this Boolean network model? Discuss 3 specific limitations

1) The state of the cell is presented in a binary manner. Although this simplifies modelling, in practice different factors are more complicated than a simple on/off binary. This may lose some nuance that would otherwise be present in some situations.

2) All of the states are updated simultaneously. Some reactions may take longer than others, a nuance which is not possible to represent in a binary model such as this one. Reactions may thus not be completely comparable to reality.

3) The interactions are simplified. Boolean logic usually cannot represent the complexity of how one protein interacts with another, though it can approximate it. Just like the other two points, this may lead to a loss of some fidelity to actual reactions in specific cases.
