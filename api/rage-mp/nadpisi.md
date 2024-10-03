---
icon: text-size
---

# Надписи
## Свойства
---
### Текст
```typescript
Label.text: string
```
### Цвет
```typescript
Label.color: Array<number>
```
### Тип шрифта
```typescript
Label.font: number
```
### Дальность отрисовки
```typescript
Label.drawDistance: number
```
### Показ через стены
```typescript
Label.los: boolean
```

## Функции
---
### Создать
```typescript
mp.labels.new(text: string, position: mp.Vector3, 
    { 
        lineOfSight: boolean, 
        fontId: number, 
        drawDistance: number, 
        color: [number, number, number, number], 
        dimension: number
    }): Label
```
