Hydeath is an essential plugin designed for Spigot, Paper, and Folia servers. It significantly enhances the gameplay experience by mitigating the frustration of losing items upon death, making the process of recovering lost items seamless and efficient.

## To Build (Linux)
```
git clone https://github.com/Androecia/hydeath.git
cd hydeath
./gradlew build
```

### config.yml
```yml
# Spread amount for dropped items
# Adjust how much the dropped items spread out when a player dies
spreadAmount: 0.2

# Item settings for dropped items
itemSettings:
  canMobPickup: true   # Allow mobs to pick up the dropped items
  invulnerable: true   # Make dropped items invulnerable
  glowing: true        # Make dropped items glow
  unlimitedLifetime: true  # Make dropped items never despawn
  sendGlobalMessage: true  # Send a global message when a player dies
```
Credit: [Easy Deaths](https://github.com/ringprod/easy-deaths)
