---
layout: home
---  

```text
 ______  _________ _______  ______   _        _______ 
(  __  \ \__   __/(  ___  )(  ___ \ ( \      (  ___  )
| (  \  )   ) (   | (   ) || (   ) )| (      | (   ) |
| |   ) |   | |   | (___) || (__/ / | |      | |   | |
| |   | |   | |   |  ___  ||  __ (  | |      | |   | |
| |   ) |   | |   | (   ) || (  \ \ | |      | |   | |
| (__/  )___) (___| )   ( || )___) )| (____/\| (___) |
(______/ \_______/|/     \||/ \___/ (_______/(_______)
                                                      
``` 

Diabloshulu the Homepage.. Developed by [hacker me](https://huludiabo.github.io/)

## ⚡ Features 

- [x] toggle light/dark with <i class="far fa-moon zoom" onclick="darkMode();"></i>
- [x] choose theme with <i class="fas fa-palette zoom" onclick="toggleTheme();"></i>
- [x] choose font with <i class="fas fa-pen-nib" onclick="toggleFont();"></i>
- [x] save current theme for next visit with <i class="fas fa-user-astronaut zoom" onclick="saveFavorite();"></i>
- [x] open/close settings with <i class="fas fa-tools zoom" onclick="toggleSettings();"></i>
- [x] clear settings with <i class="fas fa-snowplow zoom" onclick="clearSettings();"></i>   


## 💡 All About The Theme 

Theme settings are saved in [session](https://developer.mozilla.org/en-US/docs/Web/API/Window/sessionStorage) and [local](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) storage. Toggling light/dark mode or choosing a random palette saves settings for only the current session. Clicking the save button adds the theme to local storage for future visits. 


## 🍭 Default Themes 

*Try out the default themes by clicking below*


{% for themes in site.data.themes %}
<div class="theme-options {{ themes.name }} zoom" onclick="setSpeceficPallet('{{ themes.name }}');">
    <p class="center">{{ themes.name }} ~ Lorem ipsum dolor sit amet</p>
</div>
{% endfor %}  


## 👩‍🚀 Add New Themes  

Adding new themes to your new jek site could not be easier, just pick a background color and text color and add them to main.css. Once you're done, add your theme to _data/themes.yaml. Check out [colorhunt](https://colorhunt.co/) for inspiration.


1) Add a new scheme to main.css with background-color and color set.  
  
```css
.mytheme {
  background-color: #0a1d37;
  color: #ffeedb;
}
```  

2) Add a color scheme name to _data/themes.yaml.
  
```yaml
- name: mytheme
  enabled: true
```  

## ✍️ Contributing  

If you're interested in contributing to Jek, feel free to fork the repository and make a pull request! If you made a cool new theme and want to add it to the defaults, create an issue and add the [*Theme Suggestion*](https://github.com/tcbutler320/jek/labels/Theme%20Suggestion) label.  

## ⚖️ License

Licensed under [MIT](/LICENSE.txt) by [@tcbutler320](https://github.com/tcbutler320)+ [@Huludiabo](https://github.com/Huludiabo/)

## 😈 Web/Xss

Emerging from the cunning abyss, this is a ruthless, cunning, and sophistical figure in hiding. ⭐⭐⭐⭐⭐(SSR)
XSS Magic Master