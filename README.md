# 2048 Game | Игра 2048

A Qt-based implementation of the popular 2048 puzzle game.
Qt-реализация популярной игры-головоломки 2048.

## Description | Описание

[English]
This is a modern C++ implementation of the classic 2048 game using the Qt framework. Players combine numbered tiles by sliding them on a 4x4 grid, aiming to create a tile with the number 2048. The game features smooth animations, score tracking, and the ability to undo/redo moves.

[Русский]
Это современная реализация классической игры 2048 на C++ с использованием фреймворка Qt. Игроки объединяют пронумерованные плитки, перемещая их по сетке 4x4, стремясь создать плитку с числом 2048. Игра включает плавную анимацию, отслеживание счета и возможность отменять/повторять ходы.

## Features | Функциональность

[English]
- Classic 2048 gameplay mechanics with smooth animations
- Score tracking system
- Undo/Redo functionality (up to 5 moves)
- Game over detection and win condition checking
- Modern Qt-based user interface
- Keyboard controls
- New game option
- Random tile generation with 2 and 4 values

[Русский]
- Классическая механика игры 2048 с плавной анимацией
- Система подсчета очков
- Функция отмены/повтора ходов (до 5 ходов)
- Определение окончания игры и проверка условий победы
- Современный пользовательский интерфейс на Qt
- Управление с клавиатуры
- Возможность начать новую игру
- Случайная генерация плиток со значениями 2 и 4

## Technical Details | Технические детали

### Project Structure | Структура проекта

[English]
The project is structured using the following key components:

- `Game`: Core game logic and state management
- `Board`: Handles the game board operations and tile movements
- `Brick`: Represents individual tiles
- Qt UI components for visual representation

[Русский]
Проект структурирован с использованием следующих ключевых компонентов:

- `Game`: Основная логика игры и управление состоянием
- `Board`: Обработка операций на игровом поле и перемещение плиток
- `Brick`: Представляет отдельные плитки
- Компоненты пользовательского интерфейса Qt для визуального представления

## Building the Project | Сборка проекта

### Prerequisites | Предварительные условия
- Qt 6.0 or higher
- CMake 3.16 or higher
- C++17 compatible compiler

### Build Instructions | Инструкции по сборке

[English]
1. Clone the repository
2. Create a build directory:
