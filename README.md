# Dataset

This dataset provide simple informations about current [League of legends](https://lolesports.com/) esport players.

# Data structure

A player is represented by the object below :

```ts
{
  id: string; // Guid
  summonerName: string;
  firstName: string;
  lastName: string;
  birthDate: string; // JSON Date format
  team: string;
  league: string;
  picture: string; // URL of the image
}
```

## In the future

There is some data that can be stored to provide more informations about players :
- Number of international trophies
- Player's team history
- Leaguepedia's link
- TBD ...
