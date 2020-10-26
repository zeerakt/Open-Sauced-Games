# Contributions to Open Sauced Games

## Game Name
The name starts with a capital letter.
One game per file.
For instance : `[FIRST-LETTER]/[Game].json`

## File Path
Add the game to an existing folder corresponding to the starting letter of the game or create a folder if the first letter is missing.

## JSON File 

The file must contain at least 3 keys and upto 11 keys

```
Name: Name of Original 
```

``` 
repo: Link to source code
```

``` 
status: 
Must belong to 
playable
semi-playable
unplayable
```

## Example .json file (Cloned Game with three keys) 

```json
{
    "game": "Name-of-game",
    "repo": [
        "Link-to-repo"
    ],
    "status": "status"
}
```


```
## Addressing an Issue

If the game you want to add is requested in an issue, leave a comment on the issue claiming that you are adding that game. This minimizes conflicts and time wasting.
