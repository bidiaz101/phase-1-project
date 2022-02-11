# Pokemon Team Builder Plus! 
<!-- Pokemon Team Builder uses PokeAPI (https://pokeapi.co/)
to render pokemon sprites, allows user to click sprites and have the Pokemon info load in the center. It will show the pokemon name, official artwork, types, and pokemon descriptions. There is a button the generate new description text. A second button allows the user to add pokemon to their team and that pokemon appears on the right side under the "My Team" label. The user can also search by name or pokedex number. Buttons at the top of the page allow them to browse. The first and last page are conveyed by having the back and forward button disabled respectively. There is a six pokemon limit and if the user tries to add more, a error message appears notifying them of the limit. There is a button to set them free if the user would like to add a different Pokemon instead. Errors also appear if the user tries to search for a name or number that doesn't exist. -->
Everyone has heard of Pokemon. The franchise has fans worldwide, whether it be for the games, the anime, or just that they're cute! One thing I love in Pokemon, and in most games, is the lore. The time the creators take to make the story behind the gameplay brings the world to life so much more. I wanted a way to browse the fascinating stories behind the monsters while also incorporating a main feature from the games. That feature was team building. So I decided to build Pokemon Team Builder Plus! (Or "Team Builder" for short)

### Browse Pokemon

Team Builder 

<img src='https://i.imgur.com/ZgxLFwG.png' alt='Browse Buttons' style='height: 50%; width: 50%;' />
<img src='https://i.imgur.com/c0GbyI3.png' alt='Search Fields' style='height: 50%; width: 50%' />

Users can browse Pokemon using the buttons and the search field. They can either search by name, or by pokedex number. Once they select a Pokemon, that Pokemon will appear in the center as shown in the next section below.

### View Pokemon

This is how the Pokemon will appear once the user chooses one. It shows the name, an image of the pokemon, and the type/types.

<img src='https://i.imgur.com/QlVPvUf.png0' alt='Pokemon display example' style='height: 50%; width: 50%' />

They then have the option of generating more Pokedex entries and learning more about the pokemon and it's abilities by pressing the "Get More Info" button.

Two different entries are shown below.

<figure style="float: left;">
    <img src='https://i.imgur.com/lglGUeN.png' alt='Pokedex entry' />
    <img src='https://i.imgur.com/WCaB7fK.png' alt='Different Pokedex entry' />
</figure>

### Team Building 

The user will also have the option of adding the Pokemon to their team. Below the "Get More Info" button is an "Add to Team" button. This will bring the user to the top of the page, add the Pokemon's sprite to the area labeled "My Team", and temporarily highlight the added Pokemon.

<img src="https://i.imgur.com/WeOhieI.png" alt="Team Member Exxample" />

In the games, you can have a maximum of six team members and the same is true here. The user will see the error message shown below if they try to add more than six pokemon. 

<img src="https://i.imgur.com/9Rcsfhr.png" alt="Error Message">

They can add more once they click the "Set Free" button below one of their current team members. This will cause the Pokemon on their team to disappear and the user can add another in it's place.

The site is published at https://bidiaz101.github.io/pokemon-team-builder/

### Upcoming Features!

- Pokemon sprites will always appear in Pokedex order number
- The search feature will automatically filter pokemon sprites based on the current search field value
- The browse buttons will render pokemon sprites after after the initial page load
- Users will have the option to see the next Pokedex entry or generate one at random
- Video demo on the home page to show new users how it works

Thanks for sticking around 'til the end!
