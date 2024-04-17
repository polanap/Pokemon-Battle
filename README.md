# Pokemon-Battle

На основе базового класса Pokemon написаны классы для заданных видов покемонов.

![image](https://github.com/polanap/Pokemon-Battle/assets/95124950/cfcced75-a070-4192-a295-e2aca79a879b)

Каждый вид покемона имеет один или два типа и стандартные базовые характеристики:

очки здоровья (HP)
атака (attack)
защита (defense)
специальная атака (special attack)
специальная защита (special defense)
скорость (speed)
Классы покемонов наследуются в соответствии с цепочкой эволюции покемонов. Свои классы для заданных видов атак реализованы на основе базовых классов PhysicalMove, SpecialMove и StatusMove.

Атака имеет стандартные тип, силу (power) и точность (accuracy). Реализованы стандартные эффекты атаки. Каждому виду покемонов назначены атаки в соответствии с вариантом. Уровень покемона выбирается минимально необходимым для всех реализованных атак.

Класс симуляции боя Battle позволяет создать 2 команды покемонов (каждый покемон должен иметь имя) и запустить бой.
