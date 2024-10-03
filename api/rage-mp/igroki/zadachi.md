---
icon: diagram-subtask
---

# Задачи
### Достичь направления угла поворота
```typescript
Player.taskAchieveHeading(heading: number): void
```

### Нацелить оружие на координаты
```typescript
Player.taskAimGunAtCoord(x: number, y: number, z: number, duration: number): void
```

### Нацелить оружие на сущность
```typescript
Player.taskAimGunAt(entity: any, duration: number): void
```

### Нацелить оружие по скрипту
```typescript
Player.taskAimGunScripted(target: any, duration: number): void
```

### Арестовать педа
```typescript
Player.taskArrest(ped: any): void
```

### Задача для лодки
```typescript
Player.taskBoatMission(boat: any, x: number, y: number, z: number, speed: number, flag: number): void
```

### Разговор с педом
```typescript
Player.taskChatTo(ped: any, duration: number): void
```

### Очистить цель взгляда
```typescript
Player.taskClearLookAt(): void
```

### Подняться по лестнице
```typescript
Player.taskClimbLadder(ladder: any): void
```

### Подняться
```typescript
Player.taskClimb(x: number, y: number, z: number): void
```

### Бой с ненавистными целями вокруг
```typescript
Player.taskCombatHatedTargetsAround(radius: number, flags: number): void
```

### Бой с ненавистными целями в области
```typescript
Player.taskCombatHatedTargetsInArea(x: number, y: number, z: number, radius: number, flags: number): void
```

### Бой
```typescript
Player.taskCombat(target: any, flags: number): void
```

### Присесть
```typescript
Player.taskCower(duration: number): void
```

### Стрельба из машины
```typescript
Player.taskDriveBy(target: any, x: number, y: number, z: number, speed: number, flags: number): void
```

### Войти в транспортное средство
```typescript
Player.taskEnterVehicle(vehicle: any, timeout: number, seat: number, speed: number, flag: number): void
```

### Следовать по сетке навигации к координатам (расширенный)
```typescript
Player.taskFollowNavMeshToCoordAdvanced(x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void
```

### Следовать по сетке навигации к координатам
```typescript
Player.taskFollowNavMeshToCoord(x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void
```

### Следовать по маршруту точек
```typescript
Player.taskFollowPointRoute(route: any, speed: number, flags: number): void
```

### Следовать к смещению от
```typescript
Player.taskFollowToOffsetOf(entity: any, offsetX: number, offsetY: number, offsetZ: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void
```

### Принудительное состояние движения
```typescript
Player.taskForceMotionState(state: number, flags: number): void
```

### Покинуть лодку
```typescript
Player.taskGetOffBoat(boat: any): void
```

### Идти прямо к координатам
```typescript
Player.taskGoStraightToCoord(x: number, y: number, z: number, speed: number, timeout: number, targetHeading: number, unk: number, flags: number): void
```

### Идти к координатам и целиться на ненавистные сущности рядом с координатами
```typescript
Player.taskGoToCoordAndAimAtHatedEntitiesNearCoord(x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void
```

### Идти к координатам любыми средствами с дополнительными параметрами и скоростью крейсерского хода
```typescript
Player.taskGoToCoordAnyMeansExtraParamsWithCruiseSpeed(x: number, y: number, z: number, speed: number, p5: number, p6: number, p7: number, flags: number, p9: number): void
```

### Идти к координатам любыми средствами с дополнительными параметрами
```typescript
Player.taskGoToCoordAnyMeansExtraParams(x: number, y: number, z: number, speed: number, p5: number, p6: number, p7: number, flags: number, p9: number): void
```

### Идти к координатам любыми средствами
```typescript
Player.taskGoToCoordAnyMeans(x: number, y: number, z: number, speed: number, p5: number, p6: number, p7: number, flags: number, p9: number): void
```

### Идти к координатам, целясь на координаты
```typescript
Player.taskGoToCoordWhileAimingAtCoord(x: number, y: number, z: number, aimX: number, aimY: number, aimZ: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void
```

### Идти, целясь
```typescript
Player.taskGoToWhileAimingAt(entity: any, x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void
```

### Идти, целясь
```typescript
Player.taskGotoAiming(entity: any, x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void
```

### Идти к смещению
```typescript
Player.taskGotoOffset(entity: any, offsetX: number, offsetY: number, offsetZ: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void
```

### Охранять текущую позицию
```typescript
Player.taskGuardCurrentPosition(x: number, y: number, z: number, heading: number, radius: number): void
```

### Охранять сферу оборонительной области
```typescript
Player.taskGuardSphereDefensiveArea(x: number, y: number, z: number, radius: number, context: number): void
```

### Поднять руки
```typescript
Player.taskHandsUp(duration: number): void
```

### Погоня на вертолете
```typescript
Player.taskHeliChase(entity: any, x: number, y: number, z: number): void
```

### Задача для вертолета
```typescript
Player.taskHeliMission(vehicle: any, target: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void
```

### Прыжок
```typescript
Player.taskJump(): void
```

### Покинуть любое транспортное средство
```typescript
Player.taskLeaveAnyVehicle(vehicle: any, flags: number): void
```

### Покинуть транспортное средство
```typescript
Player.taskLeaveVehicle(vehicle: any, flags: number): void
```

### Смотреть на
```typescript
Player.taskLookAt(entity: any, duration: number, bone: number, aim: boolean): void
```

### Перемещение по сети (расширенное)
```typescript
Player.taskMoveNetworkAdvanced(x: number, y: number, z: number, speed: number, flags: number, entity: any, heading: number, unk: number): void
```

### Перемещение по сети
```typescript
Player.taskMoveNetwork(x: number, y: number, z: number, speed: number, flags: number, entity: any, heading: number, unk: number): void
```

### Открыть дверь транспортного средства
```typescript
Player.taskOpenVehicleDoor(vehicle: any, doorIndex: number, timeOut: number, speed: number): void
```

### Парашют к цели
```typescript
Player.taskParachuteToTarget(x: number, y: number, z: number): void
```

### Парашют
```typescript
Player.taskParachute(flag: number): void
```

### Патрулирование
```typescript
Player.taskPatrol(route: any, speed: number, flags: number): void
```

### Пауза
```typescript
Player.taskPause(duration: number): void
```

### Выполнить последовательность
```typescript
Player.taskPerformSequence(taskSequence: any): void
```

### Погоня на самолете
```typescript
Player.taskPlaneChase(entity: any, x: number, y: number, z: number): void
```

### Посадка самолета
```typescript
Player.taskPlaneLand(plane: any, x: number, y: number, z: number, heading: number): void
```

### Задача для самолета
```typescript
Player.taskPlaneMission(plane: any, target: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void
```

### Установить бомбу
```typescript
Player.taskPlantBomb(x: number, y: number, z: number, heading: number): void
```

### Воспроизвести анимацию (расширенное)
```typescript
Player.taskPlayAnimAdvanced(animDict: string, animName: string, x: number, y: number, z: number, rotX: number, rotY: number, rotZ: number, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void
```

### Воспроизвести анимацию
```typescript
Player.taskPlayAnim(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void
```

### Воспроизвести жест телефона
```typescript
Player.taskPlayPhoneGestureAnimation(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void
```

### Переместить прямо в укрытие
```typescript
Player.taskPutDirectlyIntoCover(x: number, y: number, z: number, duration: number, flags: number): void
```

### Переместить прямо в рукопашный бой
```typescript
Player.taskPutDirectlyIntoMelee(entity: any, duration: number, flags: number): void
```

### Спуститься с вертолета
```typescript
Player.taskRappelFromHeli(heli: any, x: number, y: number, z: number): void
```

### Реагировать и бежать
```typescript
Player.taskReactAndFlee(ped: any): void
```

### Перезарядить оружие
```typescript
Player.taskReloadWeapon(weaponHash: number): void
```

### Скриптовая анимация
```typescript
Player.taskScriptedAnim(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void
```

### Скриптовая анимация
```typescript
Player.taskScriptedAnimation(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void
```

### Искать укрытие от
```typescript
Player.taskSeekCoverFrom(entity: any, duration: number): void
```

### Искать укрытие к координатам
```typescript
Player.taskSeekCoverToCoords(x: number, y: number, z: number, duration: number, flags: number): void
```

### Установить блокировку временных событий
```typescript
Player.taskSetBlockingOfNonTemporaryEvents(toggle: boolean): void
```

### Установить принимателя решений
```typescript
Player.taskSetDecisionMaker(decisionMaker: any): void
```

### Реагировать на шокирующее событие
```typescript
Player.taskShockingEventReact(eventHandle: any): void
```

### Стрелять по координатам
```typescript
Player.taskShootAtCoord(x: number, y: number, z: number, duration: number, firingPattern: number): void
```

### Переместиться на следующее сиденье в транспортном средстве
```typescript
Player.taskShuffleToNextVehicleSeat(vehicle: any, p1: number): void
```

### Прыжок с парашютом
```typescript
Player.taskSkyDive(): void
```

### Скользить к координатам с углом направления
```typescript
Player.taskSlideToCoordHdgRate(x: number, y: number, z: number, heading: number, rate: number): void
```

### Скользить к координатам
```typescript
Player.taskSlideToCoord(x: number, y: number, z: number, heading: number): void
```

### Умное бегство к координатам
```typescript
Player.taskSmartFleeCoord(x: number, y: number, z: number, speed: number, duration: number, flags: number, heading: number, unk: number): void
```

### Умное бегство
```typescript
Player.taskSmartFlee(entity: any, speed: number, duration: number, flags: number, heading: number, unk: number): void
```

### Охранять
```typescript
Player.taskStandGuard(x: number, y: number, z: number, heading: number, context: number): void
```

### Стоять неподвижно
```typescript
Player.taskStandStill(duration: number): void
```

### Начать сценарий на позиции
```typescript
Player.taskStartScenarioAtPosition(scenarioName: string, x: number, y: number, z: number, heading: number, duration: number, flags: number): void
```

### Начать сценарий на месте
```typescript
Player.taskStartScenarioInPlace(scenarioName: string, duration: number, flags: number): void
```

### Оставаться в укрытии
```typescript
Player.taskStayInCover(): void
```

### Скрытое убийство
```typescript
Player.taskStealthKill(target: any, flags: number): void
```

### Остановить жест телефона
```typescript
Player.taskStopPhoneGestureAnimation(): void
```

### Поменять оружие
```typescript
Player.taskSwapWeapon(weaponHash: number): void
```

### Сканировать цель
```typescript
Player.taskSweepAim(entity: any): void
```

### Синхронизированная сцена
```typescript
Player.taskSynchronizedScene(scene: any, animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, playbackRate: number, p9: boolean): void
```

### Повернуться к координатам
```typescript
Player.taskTurnToFaceCoord(x: number, y: number, z: number, duration: number): void
```

### Повернуться к сущности
```typescript
Player.taskTurnToFace(entity: any, duration: number): void
```

### Использовать мобильный телефон (с таймером)
```typescript
Player.taskUseMobilePhoneTimed(duration: number): void
```

### Использовать мобильный телефон
```typescript
Player.taskUseMobilePhone(duration: number): void
```

### Использовать ближайший сценарий к координатам с телепортацией
```typescript
Player.taskUseNearestScenarioToCoordWarp(x: number, y: number, z: number, radius: number, flags: number): void
```

### Нацелить оружие из транспортного средства
```typescript
Player.taskVehicleAimAt(entity: any, x: number, y: number, z: number): void
```

### Погоня на транспортном средстве
```typescript
Player.taskVehicleChase(entity: any): void
```

### Водить транспортное средство к координатам (дальний маршрут)
```typescript
Player.taskVehicleDriveToCoordLongrange(vehicle: any, x: number, y: number, z: number, speed: number, driveFlags: number, stopRange: number, handlingFlags: number): void
```

### Водить транспортное средство к координатам
```typescript
Player.taskVehicleDriveToCoord(vehicle: any, x: number, y: number, z: number, speed: number, stopRange: number, handlingFlags: number, modelFlags: number, drivingFlags: number): void
```

### Водить транспортное средство по случайному маршруту
```typescript
Player.taskVehicleDriveWander(vehicle: any, speed: number, drivingStyle: number): void
```

### Эскортировать транспортное средство
```typescript
Player.taskVehicleEscort(vehicle: any, targetVehicle: any, speed: number, flags: number): void
```

### Следовать за записью маршрута
```typescript
Player.taskVehicleFollowWaypointRecording(vehicle: any, recording: any): void
```

### Следовать за транспортным средством
```typescript
Player.taskVehicleFollow(vehicle: any, targetVehicle: any, speed: number, drivingFlags: number): void
```

### Водить транспортное средство к сетке навигации
```typescript
Player.taskVehicleGotoNavmesh(vehicle: any, x: number, y: number, z: number, speed: number, stopRange: number, flags: number): void
```

### Защищать транспортное средство
```typescript
Player.taskVehicleHeliProtect(vehicle: any, target: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void
```

### Задача для транспортного средства к координатам цели
```typescript
Player.taskVehicleMissionCoorsTarget(vehicle: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void
```

### Задача для транспортного средства к цели
```typescript
Player.taskVehicleMissionTarget(vehicle: any, target: any, speed: number, radius: number, flags: number): void
```

### Припарковать транспортное средство
```typescript
Player.taskVehiclePark(vehicle: any, x: number, y: number, z: number, heading: number, radius: number, flags: number): void
```

### Стрелять из транспортного средства
```typescript
Player.taskVehicleShootAt(entity: any): void
```

### Временное действие в транспортном средстве
```typescript
Player.taskVehicleTempAction(vehicle: any, action: number, time: number): void
```

### Бродить в области
```typescript
Player.taskWanderInArea(x: number, y: number, z: number, radius: number, flags: number): void
```

### Бродить (стандарт)
```typescript
Player.taskWanderStandard(x: number, y: number, z: number, radius: number, flags: number): void
```

### Телепортироваться в транспортное средство
```typescript
Player.taskWarpIntoVehicle(vehicle: any, seat: number): void
```

### Извиваться
```typescript
Player.taskWrithe(duration: number): void
```

### Снять наручники
```typescript
Player.uncuff(): void
```
