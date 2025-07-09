# Game data from ChillyRoom games
This data is internally used by CRDE, so it is not planned to be some sort of wiki. It gets updated automatically every game release.
## Soul Knight
Structure overview:
```ts
interface GameData {
  gameVersion: string;
  appVersion: number;
  sdkVersion: string;
  weapons: string[];
  enemies: string[];
  characters: CharacterData[];
  pets: string[];
  blueprints: string[];
  achievements: number[];
  materials: string[];
  plants: string[];
  skus: string[];
}

interface CharacterData {
  codename: string;
  display_name: string;
  skill_count: number;
  skin_count: number;
}
```
