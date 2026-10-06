---

---
[[Skills/Minigames]]

```c#
//Parent Class
public createNode(type, health, maxHealth){
     private gameObject deposit = instantiate(node.prefab, this.transform, quaternion.identity);
     deposit.addComponent<depositStats.cs>().addStats(type, health, maxHealth);
     return deposit;

}
```

```c#
//depositStats.cs

//Stats:
[SerializeField]
private string type;
[SerializeField]
private int health;
[SerializeField]
private int maxHealth


public void addStats(type, health, maxHealth){
     type = type;
     health = health;
     maxHealth = maxHealth;
}
```
