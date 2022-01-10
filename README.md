# challenge-symfony-mvc
### Date:10-01-2022

## Install Symfony
- First I installed composer.
- for installing symfony-cli I have to installed first GoFish,which is a cross platform systems package manager.
- https://gofi.sh/ followed this link to install GoFish
- then installed symfony-cli with help of following commands:
 - 1. gofish rig add https://github.com/symfony-cli/fish-food
 - 2. gofish install github.com/symfony-cli/fish-food/symfony-cli
 - created new symfony application: symfony new project-name.
 - by using symfony serve command i can see symfony page on browser.
 - for creating controller,I used php bin/console make:controller but i got error as "make and bin/console not found".
 - so reinstall symfony by "composer create-project symfony/website-skeleton my_project_directory" this command and tried again to make controller,now it was worked.
 - inside controller created methods with name LearningController and add $this->render('example.twig', ['name' => 'BeCode']);
 - In template,added <h1>Hello {name}!</h1>.It shows "Hello Becode" on     browser.
 
  
