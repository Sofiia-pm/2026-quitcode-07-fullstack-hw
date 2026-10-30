# Здача WS7

## Дані

- Роль: pm
- Команда: therapy-scheduling
- GitHub-логін: Sofiia-pm
- Ваше репо: https://github.com/Sofiia-pm/therapy-scheduling-spec
- SHA: b2126030318fa9eec367cee43a08abb4033de110
- Репо вимог PM: https://github.com/Sofiia-pm/therapy-scheduling-spec
- Прод-URL: —

## PM

- Сховище вимог: issues
- Зріз 2: картка клієнта з обмеженим доступом — «Вимога: Планувальник заповнює картку клієнта з анкети, а терапевт бачить картки лише своїх клієнтів»
- Продукт — матриця прав і roadmap (A): https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/1; коментарі «Зміна: …» — https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/1#issuecomment-6361247436 (матриця прав, roadmap, глосарій, «Вигляд і тон», 23.10), https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/1#issuecomment-6426719810 (26.10)
- Вимоги зрізу 2 (B): https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/19 — створено 23.10 (AC-CARD-01…11); AC-CARD-12…16 додано 26.10 за питаннями розробників
- Відмовні AC і AC про стан інтерфейсу (B): чужі дані — AC-CARD-05, 08, 14, 16; заборонена роль — AC-CARD-06, AC-CARD-11 (без ролі), AC-HOLD-44; не увійшов — AC-CARD-07; стан інтерфейсу — AC-CARD-03, 09, 12, 15
- Самоперевірка за чеклістом (B): https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/19#issuecomment-6363178326 (з перевіркою прав)
- Питання, на які ви відповіли (C): зріз 2 — https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/20, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/21, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/22, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/23, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/24, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/25, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/26, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/27, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/28, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/29, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/30, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/31 (відповіді й зміни 26.10 — після строку 25.10, за домовленістю з командою); зріз 1 — https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/13, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/14, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/15, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/16, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/17, https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/18 (22–23.10)
- Зміни вимог із журналом змін (C): «Журнал змін» у https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/19 і https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/2; коментарі «Зміна: …» — https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/19#issuecomment-6426103398

### Приймання на проді (трек D)

| Розробник | Прод-URL | Роль (акаунт) | AC | Результат | Посилання |
|---|---|---|---|---|---|
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | scheduler (pm-scheduler@example.test) | AC-CARD-01 | ✅ | — |
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | scheduler (pm-scheduler@example.test) | AC-CARD-02 | ✅ | — |
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | scheduler (pm-scheduler@example.test) | AC-CARD-03 | ✅ | — |
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | therapist (pm-therapist@example.test) | AC-CARD-04 | ✅ | — |
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | therapist (pm-therapist@example.test) | AC-CARD-05 | ✅ | — |
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | therapist (pm-therapist@example.test) | AC-CARD-06 | ❌ | https://github.com/SnatchPlay/therapy-scheduling/issues/47 |
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | therapist (pm-therapist@example.test) | AC-HOLD-44 | ❌ | https://github.com/SnatchPlay/therapy-scheduling/issues/48 |
| @SnatchPlay | https://therapy-scheduling-weld.vercel.app | не увійшов (вікно інкогніто) | AC-CARD-07 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | scheduler (pm-scheduler@example.test) | AC-CARD-01 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | scheduler (pm-scheduler@example.test) | AC-CARD-02 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | scheduler (pm-scheduler@example.test) | AC-CARD-03 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | therapist (pm-therapist@example.test) | AC-CARD-04 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | therapist (pm-therapist@example.test) | AC-CARD-05 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | therapist (pm-therapist@example.test) | AC-CARD-06 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | therapist (pm-therapist@example.test) | AC-HOLD-44 | ✅ | — |
| @maryan-qc | https://therapy-scheduling-sigma.vercel.app | не увійшов (вікно інкогніто) | AC-CARD-07 | ✅ | — |

## Розробник

—

## Бонус

«Вигляд і тон» — розділ наприкінці «Продукту»: https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/1, додано 23.10 — https://github.com/Sofiia-pm/therapy-scheduling-spec/issues/1#issuecomment-6361247436
