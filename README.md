# pokemon-type-chart
Type Matchup Charts, showing how damage modifiers are applied when attacking and defending against Pokémon of different types. Inspired by ["An easier-to-understand version..."](http://9gag.com/gag/aD0DVpG/an-easier-to-understand-version-of-the-type-chart-of-pokemon) found on 9GAG but with added damage-mod details.

Generation 6+
---
[Online version](https://karlbishop.github.io/pokemon-type-chart/gen6)  
[Downloadable image](https://karlbishop.github.io/pokemon-type-chart/images/gen6-pokemon-type-chart.png)

Pokémon Go
---
[Online version](https://karlbishop.github.io/pokemon-type-chart/)  
[Downloadable image](https://karlbishop.github.io/pokemon-type-chart/images/pogo-pokemon-type-chart.png)

*Note*: in Pokémon Go damage modifiers have different values compared to Gen 6 (Source: [eurogamer.net](https://www.eurogamer.net/articles/2018-12-21-pokemon-go-type-chart-effectiveness-weaknesses)):  
- **Not very effective** - 0.625x damage, instead of the 0.5x damage done in the main series.
- **Super effecive** - 1.6x damage, instead of 2x damage done in the main series.
- **Immunity** - 0.39x damage, instead of 0 damage done in the main series.
- **Doubly effective** - 2.56x damage, instead of 4x damage done in the main series.

*Old Pokémon Go charts* (before immunities were added back in):  
[Online version](https://karlbishop.github.io/pokemon-type-chart/pogo_old)  
[Downloadable image](https://karlbishop.github.io/pokemon-type-chart/images/oldpogo-pokemon-type-chart.png)

*Other good charts*:  
["Easier-to-understand version..." on 9GAG](http://9gag.com/gag/aD0DVpG/an-easier-to-understand-version-of-the-type-chart-of-pokemon)  
[Pokémon Database](http://pokemondb.net/type)  
[Bulbapedia](http://bulbapedia.bulbagarden.net/wiki/Type/Type_chart)  
[Sheri-B's on Reddit](http://i.imgur.com/YpJWUB4.png) ([original post here](https://www.reddit.com/r/pokemon/comments/1oq3rg/was_getting_frustrated_finding_an_easytoread_type/))  

Uses pixelmix font by Andrew Tyler ([license](https://creativecommons.org/licenses/by-sa/3.0/us/)).

Other languages: [Français](https://github.com/KarlBishop/pokemon-type-chart/blob/gh-pages/README.fr.md)

## Running Locally

This project is built with [Jekyll](https://jekyllrb.com/) and GitHub Pages. There are two ways to run it locally:

### Option 1: Without Jekyll (No Ruby Required)

You can view the pre-built static site without installing Jekyll:

1. Clone this repository
   ```
   git clone https://github.com/KarlBishop/pokemon-type-chart.git
   cd pokemon-type-chart
   ```

2. Open the HTML files directly in your browser:
   - Open `_site/index.html` for the Pokémon Go chart
   - Open `_site/gen6.html` for the Generation 6+ chart
   - Open `_site/pogo_old.html` for the old Pokémon Go chart

   OR

3. Use a simple HTTP server:

   With Python (usually pre-installed on macOS/Linux):
   ```
   # Python 3
   cd _site
   python -m http.server 8000

   # Python 2
   cd _site
   python -m SimpleHTTPServer 8000
   ```

   Then open your browser and navigate to `http://localhost:8000`

### Option 2: With Jekyll

If you want to modify the site and rebuild it:

#### Prerequisites
- Ruby 2.7 (recommended)
- Bundler 2.1.4 or later

#### Installation
1. Clone this repository
   ```
   git clone https://github.com/KarlBishop/pokemon-type-chart.git
   cd pokemon-type-chart
   ```

2. Install dependencies
   ```
   bundle install
   ```

#### Running the site
1. Start the Jekyll server
   ```
   bundle exec jekyll serve
   ```

2. Open your browser and navigate to `http://localhost:4000`

The site will automatically refresh when you make changes to the source files.
