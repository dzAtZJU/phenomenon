# ARC

### materials

{% embed url="https://developer.apple.com/library/archive/releasenotes/ObjectiveC/RN-TransitioningToARC/Introduction/Introduction.html\#//apple\_ref/doc/uid/TP40011226-CH1-SW11" %}

### field

* memory-management
  * reference-counting
    * MRR
    * ARC

### infra

* compiler
  * code-insertion
  * code-generation

### cases-need-extra-studying

* Toll-Free-Bridging
* interoperate with code that uses MRR

### rules

check-materials

### mental-model

* \(object-graph, strong-reference, weak-reference\)
* strong-reference-cycle

### constructs

#### property-attribute

* strong
* weak

**variable-qualifier**

* \_\_strong
* \_\_weak
* \_\_unsafe\_unretained
* \_\_autoreleasing

### **questions**

* [ ] how immediately is deallocating when there is no strong reference?

\*\*\*\*





