# Grand Pattern Sim — Fleet Simulation Report

## Configuration
- **Venues**: 20 (small-world topology, p=0.3)
- **Ticks per scenario**: 1000
- **Architecture**: Mono-vibe (f64) + JEPA + CellGraph

## Scenario: Normal Operation

- **Alive venues**: 20
- **Fleet vibe**: 0.0159
- **Fleet avg surprise**: 0.0397
- **First half avg surprise**: 0.0524
- **Second half avg surprise**: 0.0245
- **Surprise reduction**: 53.2%

### Venue States (sample)

- Venue The Fractal Duck (vibe=0.041, events=139, surprise=0.023) — personality: [The Fractal Duck-shocked-9]
- Venue Quantum Bar (vibe=0.028, events=158, surprise=0.016) — personality: [nascent]
- Venue Neon Cathedral (vibe=-0.029, events=148, surprise=0.019) — personality: [nascent]
- Venue Binary Garden (vibe=-0.001, events=185, surprise=0.017) — personality: [Binary Garden-shocked-1]
- Venue Cloud Nine (vibe=-0.004, events=152, surprise=0.015) — personality: [nascent]

- **Graph connected**: true

## Scenario: Sudden Change

- **Alive venues**: 20
- **Fleet vibe**: 0.0159
- **Fleet avg surprise**: 0.0417
- **First half avg surprise**: 0.0565
- **Second half avg surprise**: 0.0245
- **Surprise reduction**: 56.6%

### Venue States (sample)

- Venue The Fractal Duck (vibe=0.041, events=139, surprise=0.023) — personality: [The Fractal Duck-shocked-12]
- Venue Quantum Bar (vibe=0.028, events=158, surprise=0.016) — personality: [nascent]
- Venue Neon Cathedral (vibe=-0.029, events=148, surprise=0.019) — personality: [nascent]
- Venue Binary Garden (vibe=-0.001, events=185, surprise=0.017) — personality: [Binary Garden-shocked-12]
- Venue Cloud Nine (vibe=-0.004, events=152, surprise=0.015) — personality: [Cloud Nine-shocked-3]

- **Graph connected**: true

## Scenario: Adversarial Injection

- **Alive venues**: 20
- **Fleet vibe**: 0.0114
- **Fleet avg surprise**: 0.0392
- **First half avg surprise**: 0.0521
- **Second half avg surprise**: 0.0237
- **Surprise reduction**: 54.5%

### Venue States (sample)

- Venue The Fractal Duck (vibe=-0.020, events=139, surprise=0.014 [CONTRARIAN]) — personality: [The Fractal Duck-shocked-9]
- Venue Quantum Bar (vibe=0.022, events=158, surprise=0.010) — personality: [nascent]
- Venue Neon Cathedral (vibe=-0.035, events=148, surprise=0.010) — personality: [nascent]
- Venue Binary Garden (vibe=-0.001, events=185, surprise=0.017) — personality: [Binary Garden-shocked-1]
- Venue Cloud Nine (vibe=-0.004, events=152, surprise=0.015) — personality: [nascent]

- **Graph connected**: true

## Scenario: New Venue Joining

- **Alive venues**: 20
- **Fleet vibe**: 0.0187
- **Fleet avg surprise**: 0.0443
- **First half avg surprise**: 0.0566
- **Second half avg surprise**: 0.0238
- **Surprise reduction**: 58.0%

### Venue States (sample)

- Venue The Fractal Duck (vibe=0.064, events=155, surprise=0.027) — personality: [The Fractal Duck-shocked-13]
- Venue Quantum Bar (vibe=0.029, events=163, surprise=0.016) — personality: [nascent]
- Venue Neon Cathedral (vibe=-0.027, events=148, surprise=0.019) — personality: [nascent]
- Venue Binary Garden (vibe=-0.001, events=192, surprise=0.017) — personality: [Binary Garden-shocked-1]
- Venue Cloud Nine (vibe=-0.004, events=155, surprise=0.015) — personality: [Cloud Nine-shocked-1]

- **Graph connected**: true

## Scenario: Venue Death

- **Alive venues**: 19
- **Fleet vibe**: 0.0182
- **Fleet avg surprise**: 0.0399
- **First half avg surprise**: 0.0524
- **Second half avg surprise**: 0.0237
- **Surprise reduction**: 54.7%

### Venue States (sample)

- Venue The Fractal Duck (vibe=0.031, events=138, surprise=0.025) — personality: [The Fractal Duck-shocked-9]
- Venue Quantum Bar (vibe=-0.016, events=157, surprise=0.015) — personality: [nascent]
- Venue Binary Garden (vibe=0.012, events=169, surprise=0.015) — personality: [Binary Garden-shocked-1]
- Venue Cloud Nine (vibe=0.070, events=151, surprise=0.066) — personality: [nascent]
- Venue The Entropy Lounge (vibe=0.052, events=176, surprise=0.020) — personality: [nascent]

- **Graph connected**: true

