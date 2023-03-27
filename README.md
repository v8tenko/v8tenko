```typescript
export const v8tenko = {
    name: 'Gleb Voitenko',
    handle: 'v8tenko',
    place: ['Russia', 'Saint-Petersburg'],
    work: {
        organization: 'toloka.ai',
        position: 'middle frontend developer'
    },
    specialization: {
        main: {
            type: 'Frontend',
            stack: ['React', 'MobX', 'TypeScript', 'Jest']
        },
        interests: ['Node.js', 'Algorithms', 'CI']
    },
    social: {
        telegram: 't.me/v8tenko',
        mail: 'v8tenko@gmail.com'
    }
} as const;
```
