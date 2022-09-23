# Simple Atom for Unity

## Introduction

We can use Unity ScriptableObjects to store data in a game project, following a Data Driven architecture. Thus, the MonoBehaviour scripts do not need depend on the other MonoBehaviour scripts. 


```mermaid
graph TD;
    MonoBehaviour A --> ScriptableObjectX;
    MonoBehaviour B --> ScriptableObjectX;
```




## References
- [How to make your code more Modular using Scriptable Objects in Unity](https://www.youtube.com/watch?v=6deqAk3jypo)
- [Three ways to architect your game with ScriptableObjects](https://unity.com/how-to/architect-game-code-scriptable-objects)