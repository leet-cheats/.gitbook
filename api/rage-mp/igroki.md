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

```markdown
## Игрок активен в сценарии
```typescript
Player.isActiveInScenario(): boolean
```

## Игрок целится из укрытия
```typescript
Player.isAimingFromCover(): boolean
```

## Игрока арестовывают
```typescript
Player.isBeingArrested(): boolean
```

## Игрока угоняют
```typescript
Player.isBeingJacked(): boolean
```

## Игрока убивают скрытно
```typescript
Player.isBeingStealthKilled(): boolean
```

## Игрока оглушают
```typescript
Player.isBeingStunned(): boolean
```

## Игрок лазает
```typescript
Player.isClimbing(): boolean
```

## Вариация компонента действительна
```typescript
Player.isComponentVariationValid(): boolean
```

## Разговор закончен
```typescript
Player.isConversationDead(): boolean
```

## Игрок в наручниках
```typescript
Player.isCuffed(): boolean
```

## Игрок мертв или умирает
```typescript
Player.isDeadOrDying(): boolean
```

## Игрок ныряет
```typescript
Player.isDiving(): boolean
```

## Игрок совершает стрельбу на ходу
```typescript
Player.isDoingDriveby(): boolean
```

### Задача стрельбы на ходу под задачей вождения
```typescript
Player.isDrivebyTaskUnderneathDrivingTask(): boolean
```

### Игрок приседает
```typescript
Player.isDucking(): boolean
```

### Игрок ныряет уклоняясь
```typescript
Player.isEvasiveDiving(): boolean
```

### Игрок смотрит на педа
```typescript
Player.isFacingPed(): boolean
```

### Игрок падает
```typescript
Player.isFalling(): boolean
```

### Игрок смертельно ранен
```typescript
Player.isFatallyInjured(): boolean
```

### Игрок бежит
```typescript
Player.isFleeing(): boolean
```

### Игрок садится в транспортное средство
```typescript
Player.isGettingIntoAVehicle(): boolean
```

### Игрок встает
```typescript
Player.isGettingUp(): boolean
```

### Игрок идет в укрытие
```typescript
Player.isGoingIntoCover(): boolean
```

### Игрок является членом группы
```typescript
Player.isGroupMember(): boolean
```

### Игрок висит на транспортном средстве
```typescript
Player.isHangingOnToVehicle(): boolean
```

### Игрок следит за педом
```typescript
Player.isHeadtrackingPed(): boolean
```

### Игрок следит
```typescript
Player.isHeadtracking(): boolean
```

### Игрок человек
```typescript
Player.isHuman(): boolean
```

### Игрок ранен
```typescript
Player.isHurt(): boolean
```

### Игрок в любой лодке
```typescript
Player.isInAnyBoat(): boolean
```

### Игрок в любом вертолете
```typescript
Player.isInAnyHeli(): boolean
```

### Игрок в любом самолете
```typescript
Player.isInAnyPlane(): boolean
```

### Игрок в любом полицейском транспорте
```typescript
Player.isInAnyPoliceVehicle(): boolean
```

### Игрок в любой подводной лодке
```typescript
Player.isInAnySub(): boolean
```

### Игрок в любом такси
```typescript
Player.isInAnyTaxi(): boolean
```

### Игрок в любом поезде
```typescript
Player.isInAnyTrain(): boolean
```

### Игрок в любом транспортном средстве
```typescript
Player.isInAnyVehicle(): boolean
```

### Игрок в бою
```typescript
Player.isInCombat(): boolean
```

### Игрок в укрытии, смотрит влево
```typescript
Player.isInCoverFacingLeft(): boolean
```

### Игрок в укрытии
```typescript
Player.isInCover(): boolean
```

### Игрок в летающем транспортном средстве
```typescript
Player.isInFlyingVehicle(): boolean
```

### Игрок в группе
```typescript
Player.isInGroup(): boolean
```

### Игрок в рукопашном бою
```typescript
Player.isInMeleeCombat(): boolean
```

### Игрок в модели
```typescript
Player.isInModel(): boolean
```

### Игрок в свободном падении с парашютом
```typescript
Player.isInParachuteFreeFall(): boolean
```

### Игрок в транспортном средстве
```typescript
Player.isInVehicle(): boolean
```

### Игрок в корчах
```typescript
Player.isInWrithe(): boolean
```

### Игрок ранен
```typescript
Player.isInjured(): boolean
```

## Игрок угоняет
```typescript
Player.isJacking(): boolean
```

### Игрок выпрыгивает из транспортного средства
```typescript
Player.isJumpingOutOfVehicle(): boolean
```

### Игрок прыгает
```typescript
Player.isJumping(): boolean
```

### Игрок мужчина
```typescript
Player.isMale(): boolean
```

### Игрок модель
```typescript
Player.isModel(): boolean
```

### Задача установки оружия под задачей вождения
```typescript
Player.isMountedWeaponTaskUnderneathDrivingTask(): boolean
```

### Игрок бежит
```typescript
Player.isMoveBlendRatioRunning(): boolean
```

### Игрок бежит быстро
```typescript
Player.isMoveBlendRatioSprinting(): boolean
```

### Игрок стоит
```typescript
Player.isMoveBlendRatioStill(): boolean
```

### Игрок идет
```typescript
Player.isMoveBlendRatioWalking(): boolean
```

### Игрок на любом мотоцикле
```typescript
Player.isOnAnyBike(): boolean
```

### Игрок пешком
```typescript
Player.isOnFoot(): boolean
```

### Игрок на горе
```typescript
Player.isOnMount(): boolean
```

### Игрок на конкретном транспортном средстве
```typescript
Player.isOnSpecificVehicle(): boolean
```

### Игрок на транспортном средстве
```typescript
Player.isOnVehicle(): boolean
```

### Игрок совершает скрытое убийство
```typescript
Player.isPerformingStealthKill(): boolean
```

### Игрок устанавливает бомбу
```typescript
Player.isPlantingBomb(): boolean
```

### Игрок использует телефонный жест
```typescript
Player.isPlayingPhoneGestureAnim(): boolean
```

### Игрок лежит
```typescript
Player.isProne(): boolean
```

### Игрок использует реквизит
```typescript
Player.isPropValid(): boolean
```

### Игрок в режиме ragdoll
```typescript
Player.isRagdoll(): boolean
```

### Игрок перезаряжает оружие
```typescript
Player.isReloading(): boolean
```

### Игрок бежит
```typescript
Player.isRunning(): boolean
```

### Игрок использует сценарий с условной анимацией
```typescript
Player.isScriptedScenarioUsingConditionalAnim(): boolean
```

### Игрок стреляет в области
```typescript
Player.isShootingInArea(): boolean
```

### Игрок стреляет
```typescript
Player.isShooting(): boolean
```

### Игрок сидит в любом транспортном средстве
```typescript
Player.isSittingInAnyVehicle(): boolean
```

### Игрок сидит в транспортном средстве
```typescript
Player.isSittingInVehicle(): boolean
```

### Игрок бежит быстро
```typescript
Player.isSprinting(): boolean
```

### Игрок стоит
```typescript
Player.isStill(): boolean
```

### Игрок остановился
```typescript
Player.isStopped(): boolean
```

### Игрок двигается боком
```typescript
Player.isStrafing(): boolean
```

### Игрок плавает под водой
```typescript
Player.isSwimmingUnderWater(): boolean
```

### Игрок плавает
```typescript
Player.isSwimming(): boolean
```

### Игрок отслеживается и виден
```typescript
Player.isTrackedVisible(): boolean
```

### Игрок отслеживается
```typescript
Player.isTracked(): boolean
```

### Игрок пытается войти в закрытое транспортное средство
```typescript
Player.isTryingToEnterALockedVehicle(): boolean
```

### Игрок использует режим действия
```typescript
Player.isUsingActionMode(): boolean
```

### Игрок использует любой сценарий
```typescript
Player.isUsingAnyScenario(): boolean
```

### Игрок использует сценарий
```typescript
Player.isUsingScenario(): boolean
```

### Игрок перепрыгивает
```typescript
Player.isVaulting(): boolean
```

### Игрок идет
```typescript
Player.isWalking(): boolean
```

### Игрок носит шлем
```typescript
Player.isWearingHelmet(): boolean
```

### Игрок выполняет задачу arrest
```typescript
Player.isRunningArrestTask(): boolean
```

### Игрок выполняет задачу mobile phone
```typescript
Player.isRunningMobilePhoneTask(): boolean
```

### Игрок выполняет задачу ragdoll
```typescript
Player.isRunningRagdollTask(): boolean
```

## Задачи
---

### Достичь направления угла поворота
```typescript
Player.taskAchieveHeading(heading: number): void;
```

### Нацелить оружие на координаты
```typescript
Player.taskAimGunAtCoord(x: number, y: number, z: number, duration: number): void;
```

### Нацелить оружие на сущность
```typescript
Player.taskAimGunAt(entity: any, duration: number): void;
```

### Нацелить оружие по скрипту
```typescript
Player.taskAimGunScripted(target: any, duration: number): void;
```

### Арестовать педа
```typescript
Player.taskArrest(ped: any): void;
```

### Задача для лодки
```typescript
Player.taskBoatMission(boat: any, x: number, y: number, z: number, speed: number, flag: number): void;
```

### Разговор с педом
```typescript
Player.taskChatTo(ped: any, duration: number): void;
```

### Очистить цель взгляда
```typescript
Player.taskClearLookAt(): void;
```

### Подняться по лестнице
```typescript
Player.taskClimbLadder(ladder: any): void;
```

### Подняться
```typescript
Player.taskClimb(x: number, y: number, z: number): void;
```

### Бой с ненавистными целями вокруг
```typescript
Player.taskCombatHatedTargetsAround(radius: number, flags: number): void;
```

### Бой с ненавистными целями в области
```typescript
Player.taskCombatHatedTargetsInArea(x: number, y: number, z: number, radius: number, flags: number): void;
```

### Бой
```typescript
Player.taskCombat(target: any, flags: number): void;
```

### Присесть
```typescript
Player.taskCower(duration: number): void;
```

### Стрельба из машины
```typescript
Player.taskDriveBy(target: any, x: number, y: number, z: number, speed: number, flags: number): void;
```

### Войти в транспортное средство
```typescript
Player.taskEnterVehicle(vehicle: any, timeout: number, seat: number, speed: number, flag: number): void;
```

### Следовать по сетке навигации к координатам (расширенный)
```typescript
Player.taskFollowNavMeshToCoordAdvanced(x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void;
```

### Следовать по сетке навигации к координатам
```typescript
Player.taskFollowNavMeshToCoord(x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void;
```

### Следовать по маршруту точек
```typescript
Player.taskFollowPointRoute(route: any, speed: number, flags: number): void;
```

### Следовать к смещению от
```typescript
Player.taskFollowToOffsetOf(entity: any, offsetX: number, offsetY: number, offsetZ: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void;
```

### Принудительное состояние движения
```typescript
Player.taskForceMotionState(state: number, flags: number): void;
```

### Покинуть лодку
```typescript
Player.taskGetOffBoat(boat: any): void;
```

### Идти прямо к координатам
```typescript
Player.taskGoStraightToCoord(x: number, y: number, z: number, speed: number, timeout: number, targetHeading: number, unk: number, flags: number): void;
```

### Идти к координатам и целиться на ненавистные сущности рядом с координатами
```typescript
Player.taskGoToCoordAndAimAtHatedEntitiesNearCoord(x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void;
```

### Идти к координатам любыми средствами с дополнительными параметрами и скоростью крейсерского хода
```typescript
Player.taskGoToCoordAnyMeansExtraParamsWithCruiseSpeed(x: number, y: number, z: number, speed: number, p5: number, p6: number, p7: number, flags: number, p9: number): void;
```

### Идти к координатам любыми средствами с дополнительными параметрами
```typescript
Player.taskGoToCoordAnyMeansExtraParams(x: number, y: number, z: number, speed: number, p5: number, p6: number, p7: number, flags: number, p9: number): void;
```

### Идти к координатам любыми средствами
```typescript
Player.taskGoToCoordAnyMeans(x: number, y: number, z: number, speed: number, p5: number, p6: number, p7: number, flags: number, p9: number): void;
```

### Идти к координатам, целясь на координаты
```typescript
Player.taskGoToCoordWhileAimingAtCoord(x: number, y: number, z: number, aimX: number, aimY: number, aimZ: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void;
```

### Идти, целясь
```typescript
Player.taskGoToWhileAimingAt(entity: any, x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void;
```

### Идти, целясь
```typescript
Player.taskGotoAiming(entity: any, x: number, y: number, z: number, speed: number, timeout: number, stoppingRange: number, flags: number, aimingFlags: number, firingPattern: number): void;
```

### Идти к смещению
```typescript
Player.taskGotoOffset(entity: any, offsetX: number, offsetY: number, offsetZ: number, speed: number, timeout: number, stoppingRange: number, flags: number, heading: number, unk: number): void;
```

### Охранять текущую позицию
```typescript
Player.taskGuardCurrentPosition(x: number, y: number, z: number, heading: number, radius: number): void;
```

### Охранять сферу оборонительной области
```typescript
Player.taskGuardSphereDefensiveArea(x: number, y: number, z: number, radius: number, context: number): void;
```

### Поднять руки
```typescript
Player.taskHandsUp(duration: number): void;
```

### Погоня на вертолете
```typescript
Player.taskHeliChase(entity: any, x: number, y: number, z: number): void;
```

### Задача для вертолета
```typescript
Player.taskHeliMission(vehicle: any, target: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void;
```

### Прыжок
```typescript
Player.taskJump(): void;
```

### Покинуть любое транспортное средство
```typescript
Player.taskLeaveAnyVehicle(vehicle: any, flags: number): void;
```

### Покинуть транспортное средство
```typescript
Player.taskLeaveVehicle(vehicle: any, flags: number): void;
```

### Смотреть на
```typescript
Player.taskLookAt(entity: any, duration: number, bone: number, aim: boolean): void;
```

### Перемещение по сети (расширенное)
```typescript
Player.taskMoveNetworkAdvanced(x: number, y: number, z: number, speed: number, flags: number, entity: any, heading: number, unk: number): void;
```

### Перемещение по сети
```typescript
Player.taskMoveNetwork(x: number, y: number, z: number, speed: number, flags: number, entity: any, heading: number, unk: number): void;
```

### Открыть дверь транспортного средства
```typescript
Player.taskOpenVehicleDoor(vehicle: any, doorIndex: number, timeOut: number, speed: number): void;
```

### Парашют к цели
```typescript
Player.taskParachuteToTarget(x: number, y: number, z: number): void;
```

### Парашют
```typescript
Player.taskParachute(flag: number): void;
```

### Патрулирование
```typescript
Player.taskPatrol(route: any, speed: number, flags: number): void;
```

### Пауза
```typescript
Player.taskPause(duration: number): void;
```

### Выполнить последовательность
```typescript
Player.taskPerformSequence(taskSequence: any): void;
```

### Погоня на самолете
```typescript
Player.taskPlaneChase(entity: any, x: number, y: number, z: number): void;
```

### Посадка самолета
```typescript
Player.taskPlaneLand(plane: any, x: number, y: number, z: number, heading: number): void;
```

### Задача для самолета
```typescript
Player.taskPlaneMission(plane: any, target: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void;
```

### Установить бомбу
```typescript
Player.taskPlantBomb(x: number, y: number, z: number, heading: number): void;
```

### Воспроизвести анимацию (расширенное)
```typescript
Player.taskPlayAnimAdvanced(animDict: string, animName: string, x: number, y: number, z: number, rotX: number, rotY: number, rotZ: number, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void;
```

### Воспроизвести анимацию
```typescript
Player.taskPlayAnim(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void;
```

### Воспроизвести жест телефона
```typescript
Player.taskPlayPhoneGestureAnimation(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void;
```

### Переместить прямо в укрытие
```typescript
Player.taskPutDirectlyIntoCover(x: number, y: number, z: number, duration: number, flags: number): void;
```

### Переместить прямо в рукопашный бой
```typescript
Player.taskPutDirectlyIntoMelee(entity: any, duration: number, flags: number): void;
```

### Спуститься с вертолета
```typescript
Player.taskRappelFromHeli(heli: any, x: number, y: number, z: number): void;
```

### Реагировать и бежать
```typescript
Player.taskReactAndFlee(ped: any): void;
```

### Перезарядить оружие
```typescript
Player.taskReloadWeapon(weaponHash: number): void;
```

### Скриптовая анимация
```typescript
Player.taskScriptedAnim(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void;
```

### Скриптовая анимация
```typescript
Player.taskScriptedAnimation(animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, animFlags: number, playbackRate: number): void;
```

### Искать укрытие от
```typescript
Player.taskSeekCoverFrom(entity: any, duration: number): void;
```

### Искать укрытие к координатам
```typescript
Player.taskSeekCoverToCoords(x: number, y: number, z: number, duration: number, flags: number): void;
```

### Установить блокировку временных событий
```typescript
Player.taskSetBlockingOfNonTemporaryEvents(toggle: boolean): void;
```

### Установить принимателя решений
```typescript
Player.taskSetDecisionMaker(decisionMaker: any): void;
```

### Реагировать на шокирующее событие
```typescript
Player.taskShockingEventReact(eventHandle: any): void;
```

### Стрелять по координатам
```typescript
Player.taskShootAtCoord(x: number, y: number, z: number, duration: number, firingPattern: number): void;
```

### Переместиться на следующее сиденье в транспортном средстве
```typescript
Player.taskShuffleToNextVehicleSeat(vehicle: any, p1: number): void;
```

### Прыжок с парашютом
```typescript
Player.taskSkyDive(): void;
```

### Скользить к координатам с углом направления
```typescript
Player.taskSlideToCoordHdgRate(x: number, y: number, z: number, heading: number, rate: number): void;
```

### Скользить к координатам
```typescript
Player.taskSlideToCoord(x: number, y: number, z: number, heading: number): void;
```

### Умное бегство к координатам
```typescript
Player.taskSmartFleeCoord(x: number, y: number, z: number, speed: number, duration: number, flags: number, heading: number, unk: number): void;
```

### Умное бегство
```typescript
Player.taskSmartFlee(entity: any, speed: number, duration: number, flags: number, heading: number, unk: number): void;
```

### Охранять
```typescript
Player.taskStandGuard(x: number, y: number, z: number, heading: number, context: number): void;
```

### Стоять неподвижно
```typescript
Player.taskStandStill(duration: number): void;
```

### Начать сценарий на позиции
```typescript
Player.taskStartScenarioAtPosition(scenarioName: string, x: number, y: number, z: number, heading: number, duration: number, flags: number): void;
```

### Начать сценарий на месте
```typescript
Player.taskStartScenarioInPlace(scenarioName: string, duration: number, flags: number): void;
```

### Оставаться в укрытии
```typescript
Player.taskStayInCover(): void;
```

### Скрытое убийство
```typescript
Player.taskStealthKill(target: any, flags: number): void;
```

### Остановить жест телефона
```typescript
Player.taskStopPhoneGestureAnimation(): void;
```

### Поменять оружие
```typescript
Player.taskSwapWeapon(weaponHash: number): void;
```

### Сканировать цель
```typescript
Player.taskSweepAim(entity: any): void;
```

### Синхронизированная сцена
```typescript
Player.taskSynchronizedScene(scene: any, animDict: string, animName: string, speed: number, speedMultiplier: number, duration: number, flag: number, playbackRate: number, p9: boolean): void;
```

### Повернуться к координатам
```typescript
Player.taskTurnToFaceCoord(x: number, y: number, z: number, duration: number): void;
```

### Повернуться к сущности
```typescript
Player.taskTurnToFace(entity: any, duration: number): void;
```

### Использовать мобильный телефон (с таймером)
```typescript
Player.taskUseMobilePhoneTimed(duration: number): void;
```

### Использовать мобильный телефон
```typescript
Player.taskUseMobilePhone(duration: number): void;
```

### Использовать ближайший сценарий к координатам с телепортацией
```typescript
Player.taskUseNearestScenarioToCoordWarp(x: number, y: number, z: number, radius: number, flags: number): void;
```

### Нацелить оружие из транспортного средства
```typescript
Player.taskVehicleAimAt(entity: any, x: number, y: number, z: number): void;
```

### Погоня на транспортном средстве
```typescript
Player.taskVehicleChase(entity: any): void;
```

### Водить транспортное средство к координатам (дальний маршрут)
```typescript
Player.taskVehicleDriveToCoordLongrange(vehicle: any, x: number, y: number, z: number, speed: number, driveFlags: number, stopRange: number, handlingFlags: number): void;
```

### Водить транспортное средство к координатам
```typescript
Player.taskVehicleDriveToCoord(vehicle: any, x: number, y: number, z: number, speed: number, stopRange: number, handlingFlags: number, modelFlags: number, drivingFlags: number): void;
```

### Водить транспортное средство по случайному маршруту
```typescript
Player.taskVehicleDriveWander(vehicle: any, speed: number, drivingStyle: number): void;
```

### Эскортировать транспортное средство
```typescript
Player.taskVehicleEscort(vehicle: any, targetVehicle: any, speed: number, flags: number): void;
```

### Следовать за записью маршрута
```typescript
Player.taskVehicleFollowWaypointRecording(vehicle: any, recording: any): void;
```

### Следовать за транспортным средством
```typescript
Player.taskVehicleFollow(vehicle: any, targetVehicle: any, speed: number, drivingFlags: number): void;
```

### Водить транспортное средство к сетке навигации
```typescript
Player.taskVehicleGotoNavmesh(vehicle: any, x: number, y: number, z: number, speed: number, stopRange: number, flags: number): void;
```

### Защищать транспортное средство
```typescript
Player.taskVehicleHeliProtect(vehicle: any, target: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void;
```

### Задача для транспортного средства к координатам цели
```typescript
Player.taskVehicleMissionCoorsTarget(vehicle: any, x: number, y: number, z: number, speed: number, radius: number, flags: number): void;
```

### Задача для транспортного средства к цели
```typescript
Player.taskVehicleMissionTarget(vehicle: any, target: any, speed: number, radius: number, flags: number): void;
```

### Припарковать транспортное средство
```typescript
Player.taskVehiclePark(vehicle: any, x: number, y: number, z: number, heading: number, radius: number, flags: number): void;
```

### Стрелять из транспортного средства
```typescript
Player.taskVehicleShootAt(entity: any): void;
```

### Временное действие в транспортном средстве
```typescript
Player.taskVehicleTempAction(vehicle: any, action: number, time: number): void;
```

### Бродить в области
```typescript
Player.taskWanderInArea(x: number, y: number, z: number, radius: number, flags: number): void;
```

### Бродить (стандарт)
```typescript
Player.taskWanderStandard(x: number, y: number, z: number, radius: number, flags: number): void;
```

### Телепортироваться в транспортное средство
```typescript
Player.taskWarpIntoVehicle(vehicle: any, seat: number): void;
```

### Извиваться
```typescript
Player.taskWrithe(duration: number): void;
```

### Снять наручники
```typescript
Player.uncuff(): void;
```
