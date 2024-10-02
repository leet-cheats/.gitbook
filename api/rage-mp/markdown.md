---
icon: text-size
---

# Надписи

### Создать надпись

{% code fullWidth="false" %}
```typescript
mp.labels.new(text: string, position: mp.Vector3, 
    { 
        lineOfSight: boolean, 
        fontId: number, 
        drawDistance: number, 
        color: [number, number, number, number], 
        dimension: number
    }): mp.Label
```
{% endcode %}

### Уничтожить надпись

```typescript
mp.Label.destroy(): void
```

