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



## ⚡ Features

+ [x] toggle light/dark
+ [x] choose custom theme 
+ [x] choose custom font 
+ [x] save current theme for next visit
+ [x] open/close settings
+ [x] clear settings 

## 💡 All About The Theme 

Theme settings are saved in [session](https://developer.mozilla.org/en-US/docs/Web/API/Window/sessionStorage) and [local](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage) storage. Toggling light/dark mode or choosing a random palette saves settings for only the current session. Clicking the save button adds the theme to local storage for future visits. 

## 🍭 Default Themes 

![Demo video](/assets/img/readme/jek.gif)

## 👩‍🚀 Add New Themes  

Adding new themes to your new jek site could not be easier. Just pick a background color and text color and add them to your `main.css`. Once you're done, add your theme to `_data/themes.yaml`. Check out [colorhunt](https://colorhunt.co/) for inspiration.

1. Add a new scheme to your `main.css` with `background-color` and `color` set.  
    ```css
    .mytheme {
      background-color: #0a1d37;
      color: #ffeedb;
    }
    ```  
2. Add a color scheme name to your `_data/themes.yaml`.  
    ```yaml
    - name: mytheme
      enabled: true
    ```

## ✍️ Contributing  

If you're interested in contributing to Jek, feel free to fork the repository and make a pull request! If you made a cool new theme and want to add it to the defaults, create an issue and add the [*Theme Suggestion*](https://github.com/tcbutler320/jek/labels/Theme%20Suggestion) label.  

## ⚖️ License

Licensed under [MIT](/LICENSE.txt) by [@tcbutler320](https://github.com/tcbutler320).
