# Обновление от 21.07.2026
- Был снова запущен перевод всей игры (Текстовой части) на более мощной модели.
- translation_cache был изменён! С этого момента он более не изменится, но на крайний случай я сделал скрипт, который синхронизирует разные версии кэша.
- Оригинальная папка была синхронизированна с переведённой. Чисто для удобства мне, в первую очередь.
- Начата работа с графическими элементами игры, на этот раз без ИИ.

> Так же, хочу найти человека (либо группу), кто готов БЕСПЛАТНО, только на добровольной основе, помогать с локализацией графической части игры. Требуется умение работы в Photoshop и умение работать на графическом планшете, если имеется. Уточню, что если мне придут деньги на кошелёк, а это мало вероятно, то я их разделю, но по вкладу работы, если вообще кто-то будет этим заниматься :) Человек я не злой и мне не жалко отдать пожертвования для людей, кто бесплатно это делает. 

<details>
<summary><b>Текущий прогресс локализации</b></summary>

| Файл локализации | Всего строк | Готово | Статус |
| :--- | :---: | :---: | :--- |
| `ads/ads.json` | 27 | 27 | ✅ Готов |
| `archived_content/archived_content.json` | 28 | 28 | ✅ Готов |
| `attackmodes/attackmodes.json` | 83 | 83 | ✅ Готов |
| `attackmodes/attackmodes_plots.json` | 3 | 3 | ✅ Готов |
| `careers/careers.json` | 12 | 12 | ✅ Готов |
| `conditions/conditions.json` | 2347 | 2335 | ⏳ В процессе (99.5%) |
| `conditions/conditions_pda.json` | 77 | 77 | ✅ Готов |
| `conditions/conditions_plots.json` | 1011 | 916 | ⏳ В процессе (90.6%) |
| `conditions/conditions_plots_3act.json` | 4 | 0 | ⏳ В процессе (0.0%) |
| `conditions/conditions_stakes.json` | 6 | 6 | ✅ Готов |
| `conditions_simple/conditions_simple.json` | 2378 | 2136 | ⏳ В процессе (89.8%) |
| `condowners/condowners.json` | 1831 | 1798 | ⏳ В процессе (98.2%) |
| `condowners/condowners_chargers.json` | 40 | 40 | ✅ Готов |
| `condowners/condowners_combat.json` | 107 | 107 | ✅ Готов |
| `condowners/condowners_meat.json` | 34 | 34 | ✅ Готов |
| `condowners/condowners_reactor.json` | 144 | 144 | ✅ Готов |
| `condowners/condowners_smoking.json` | 45 | 45 | ✅ Готов |
| `condowners/condowners_wounds.json` | 40 | 40 | ✅ Готов |
| `context/context.json` | 8 | 8 | ✅ Готов |
| `cooverlays/cooverlays.json` | 150 | 147 | ⏳ В процессе (98.0%) |
| `cooverlays/cooverlays_body.json` | 60 | 60 | ✅ Готов |
| `cooverlays/cooverlays_clothes.json` | 217 | 217 | ✅ Готов |
| `cooverlays/cooverlays_containers.json` | 120 | 120 | ✅ Готов |
| `cooverlays/cooverlays_datafiles.json` | 110 | 58 | ⏳ В процессе (52.7%) |
| `cooverlays/cooverlays_floors.json` | 360 | 360 | ✅ Готов |
| `cooverlays/cooverlays_markets.json` | 38 | 38 | ✅ Готов |
| `cooverlays/cooverlays_plots.json` | 4 | 4 | ✅ Готов |
| `cooverlays/cooverlays_traders.json` | 53 | 53 | ✅ Готов |
| `cooverlays/cooverlays_walls.json` | 84 | 84 | ✅ Готов |
| `headlines/headlines.json` | 43 | 43 | ✅ Готов |
| `info/infoNodes.json` | 174 | 59 | ⏳ В процессе (33.9%) |
| `installables/installables.json` | 771 | 771 | ✅ Готов |
| `installables/installables_dismantle.json` | 233 | 233 | ✅ Готов |
| `installables/installables_repair.json` | 197 | 197 | ✅ Готов |
| `installables/installables_undamage.json` | 386 | 386 | ✅ Готов |
| `interactions/interactions.json` | 1571 | 1563 | ⏳ В процессе (99.5%) |
| `interactions/interactions2.json` | 678 | 678 | ✅ Готов |
| `interactions/interactions_autofactions.json` | 15 | 15 | ✅ Готов |
| `interactions/interactions_combat.json` | 203 | 203 | ✅ Готов |
| `interactions/interactions_datafiles.json` | 296 | 270 | ⏳ В процессе (91.2%) |
| `interactions/interactions_debug.json` | 22 | 22 | ✅ Готов |
| `interactions/interactions_encounters.json` | 418 | 415 | ⏳ В процессе (99.3%) |
| `interactions/interactions_events.json` | 58 | 58 | ✅ Готов |
| `interactions/interactions_events_ffwd.json` | 176 | 176 | ✅ Готов |
| `interactions/interactions_fixer.json` | 48 | 48 | ✅ Готов |
| `interactions/interactions_hacking.json` | 68 | 68 | ✅ Готов |
| `interactions/interactions_honeypot.json` | 19 | 19 | ✅ Готов |
| `interactions/interactions_modeswitch.json` | 533 | 532 | ⏳ В процессе (99.8%) |
| `interactions/interactions_pledges.json` | 362 | 362 | ✅ Готов |
| `interactions/interactions_plots.json` | 1197 | 1196 | ⏳ В процессе (99.9%) |
| `interactions/interactions_plots_3act.json` | 10 | 10 | ✅ Готов |
| `interactions/interactions_plots_meat.json` | 255 | 254 | ⏳ В процессе (99.6%) |
| `interactions/interactions_plots_merga.json` | 376 | 256 | ⏳ В процессе (68.1%) |
| `interactions/interactions_plots_whodunnit.json` | 521 | 521 | ✅ Готов |
| `interactions/interactions_port_authority.json` | 64 | 64 | ✅ Готов |
| `interactions/interactions_relationships.json` | 257 | 257 | ✅ Готов |
| `interactions/interactions_ship_to_ship.json` | 256 | 252 | ⏳ В процессе (98.4%) |
| `interactions/interactions_slots.json` | 124 | 124 | ✅ Готов |
| `interactions/interactions_slots_wield.json` | 126 | 126 | ✅ Готов |
| `interactions/interactions_social_core.json` | 24 | 24 | ✅ Готов |
| `interactions/interactions_stk_template.json` | 204 | 182 | ⏳ В процессе (89.2%) |
| `ledgerdefs/ledgerdefs.json` | 86 | 82 | ⏳ В процессе (95.3%) |
| `market/Production/production_maps.json` | 239 | 239 | ✅ Готов |
| `pledges/pledges.json` | 68 | 68 | ✅ Готов |
| `plots/plots.json` | 34 | 0 | ⏳ В процессе (0.0%) |
| `racing/leagues/leagues.json` | 5 | 5 | ✅ Готов |
| `racing/tracks/racetracks.json` | 8 | 8 | ✅ Готов |
| `rooms/rooms.json` | 18 | 18 | ✅ Готов |
| `slots/slots.json` | 66 | 66 | ✅ Готов |
| `slots/slots_wounds.json` | 40 | 40 | ✅ Готов |
| `star_systems/star_system.json` | 15 | 1 | ⏳ В процессе (6.7%) |
| `star_systems/test_environments.json` | 86 | 8 | ⏳ В процессе (9.3%) |
| `strings/strings.json` | 904 | 878 | ⏳ В процессе (97.1%) |
| `tips/tips.json` | 23 | 23 | ✅ Готов |

### Итоговая сводка по проекту
* **Завершено файлов:** `296` из `318`
* **Всего строк в игре:** `20 698`
* **Переведено строк:** `19 800`
* **Общий прогресс:** **`95.66%`**

</details>

# Ostranauts — Русификатор (ИИ-перевод)

Добро пожаловать! Данный репозиторий создан для тех, кто хочет насладиться великолепной игрой **Ostranauts**, но испытывает трудности с английским языком. 

> ⚠️ **ВАЖНО:** Перевод выполнен с помощью локальной языковой модели `qwen3-4b-instruct`. Он **НЕ ПОЛНЫЙ** и может содержать смысловые или грамматические ошибки (например: *"You are сел на стул"*). 

Цель проекта — сделать игру доступной уже сейчас, силами автоматизации, так как объём текста в игре огромный. Работа над улучшением ведется постоянно!
### Так же хотел бы уточнить: ИИ перевод сделан на быструю руку, чтобы сделать большую часть рутинной работы. Я, в данный момент это делаю один, поэтому иду на уступки данного рода.

---

## Что уже сделано
* **Объем:** Переведено в районе **13 000 строк** текста.
* **Покрытие:** Основные сюжетные и геймплейные моменты полностью играбельны.
* **Планы:** В будущем планируется перевод текстур и графических ассетов.

---

## 🛠️ Как помочь проекту

Если вы хотите улучшить перевод, исправить машинный контекст или ускорить процесс, я буду рад вашей помощи!

1. Перейдите в соседнюю ветку репозитория.
2. Найдите файл **кэша перевода**. Он записан в формате: `"English Text": "Russian Text"`.
3. Номера строк статичны и не меняются.
4. Вы можете присылать свои правки через **Pull Requests** или в раздел **Issues**, обязательно указывая **номер строки** или **English Text**.

---

## Поддержать автора

Создание и поддержка локальной ИИ-модели для перевода тысяч строк требует времени и вычислительных ресурсов. Если вы хотите материально ускорить выход обновлений, вы можете сделать это абсолютно анонимно:

* **Crypto (USDT TRC-20):** `TCX2B7eNEahv9cQYDh3G5b3uxDZgznUdEP`

---

## Скриншоты

<details>
<summary><b>Нажмите, чтобы развернуть галерею (13 фото)</b></summary>
<p align="center">
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_1.png" alt="Ostranauts Gameplay 1" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_2.png" alt="Ostranauts Gameplay 2" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_3.png" alt="Ostranauts Gameplay 3" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_4.png" alt="Ostranauts Gameplay 4" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_5.png" alt="Ostranauts Gameplay 5" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_6.png" alt="Ostranauts Gameplay 6" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_7.png" alt="Ostranauts Gameplay 7" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_8.png" alt="Ostranauts Gameplay 8" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_9.png" alt="Ostranauts Gameplay 9" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_10.png" alt="Ostranauts Gameplay 10" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_11.png" alt="Ostranauts Gameplay 11" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_12.png" alt="Ostranauts Gameplay 12" width="80%"><br><br>
  <img src="https://raw.githubusercontent.com/KubeRube-coder/ostranauts-rus-translate/refs/heads/cache-clean/img/Screenshot_13.png" alt="Ostranauts Gameplay 13" width="80%"><br>
</p>
</details>