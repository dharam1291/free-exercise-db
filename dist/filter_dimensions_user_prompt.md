# User message template

Use this as the **user** role content per request. Substitute the placeholders from your app.

---

## USER_CONTEXT

```json
${USER_CONTEXT}
```

## ALLOWED_VALUES

Only these strings may appear in your output (arrays below are allow-lists per field):

```json
{
  "goal": ${GOAL_ENUM},
  "level": ${LEVEL_ENUM},
  "fatigue_level": ${FATIGUE_ENUM},
  "injury_risk": ${INJURY_RISK_ENUM},
  "category": ${CATEGORY_ENUM},
  "muscle_group": ${MUSCLE_GROUP_ENUM},
  "concepts": ${SUITABLE_FOR_CONCEPTS},
  "avoid_groups": ${AVOID_GROUPS}
}
```

Return the exercise filter JSON only.
