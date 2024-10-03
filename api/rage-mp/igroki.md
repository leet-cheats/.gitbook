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
