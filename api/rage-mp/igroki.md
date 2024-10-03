---
icon: users
---

# Игроки

## Здоровье
### Получить
```typescript
Player.getHealth(): number
```
### Установить
```
Player.setHealth(healthAmount: number): void
```
### Получить максимальное
```typescript
Player.getMaxHealth(): number
```
### Установить максимальное
```typescript
Player.setMaxHealth(maxHealthAmount: number): void
```

## Броня
### Получить
```typescript
Player.getArmour(): number
```
### Установить
```typescript
Player.setArmour(armourAmount: number): void
```
### Добавить
```typescript
Player.addArmourTo(armourAmount: number): void
```

## Урон
### Применить
```typescript
Player.applyDamageTo(damageAmount: number, includingArmor: boolean);
```

## Состояние
---
### Является игроком
Функция возвращает `true`, если данный пешеход имеет действительный указатель на `CPlayerInfo` в своем классе `CPed`.
```typescript
Player.isAPlayer(): boolean
```

### Падает
```typescript
Player.isFalling(): boolean
```

### Ранен
```typescript
Player.isHurt(): boolean
```

### Находится в лодке
```typescript
Player.isInAnyBoat(): boolean
```

### Находится в вертолёте
```typescript
Player.isInAnyHeli(): boolean
```

### Находится в самолёте
```typescript
Player.isInAnyPlane(): boolean
```

### Находится в полицейской машине
```typescript
Player.isInAnyPoliceVehicle(): boolean
```
