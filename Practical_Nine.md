# Week Ten - Practical Nine

## Learning Activities

This week, aside from the immense amount of work needing to be done with the group assessment, I have spent the week learning how to implement gulp task runners in the local development environment. Mostly Gulp would be employed for automatically converting sass files into usable css files when changes are made in development. This also extended to using PHPStorm IDE plugins to effectively watch the file changes and also convert the scss to css.

## Resources/Links

[PHPStorm File Watchers](https://www.jetbrains.com/help/phpstorm/transpiling-sass-less-and-scss-to-css.html#ws_sass_less_scss_example_scss)\
[Gulp Docker Container](https://github.com/suthanbala/wordpress-docker-gulp)\
[Gulp-Sass Repo](https://github.com/dlmanning/gulp-sass)

## Estimated Hours

~4 hours

## Content Insights

The learning/research this week took longer than I was originally expecting. This was mostly because I had the misconception that the Scss/css conversion had to happen on a live server and thus we needed to figure out how to also deploy a Gulp docker container to the live site to handle the conversions. It wasn't until I read through the Gulp-Sass repo that I became aware of the fact that it did not need to be on the live site, as the css files would be converted ahead of deploying the Wordpress site. This meant that I had to install, test and use trial-and-error to get Gulp and the associated Node modules and dependencies working to begin developing using scss.

## Career/Employability/Learning Insights

From a career or employability perspective, this experience has given me a number of insights into my own process. It has highlighted the importance of conducting thorough research and planning to better understand the project and avoid misconceptions or incorrect assumptions. This could save valuable development time and resources. The experience also highlighted the importance of being adaptable and flexible. The ability to adapt to situations and learn new skills quickly are valued by many career employers. In any career, there will be times when you encounter unexpected challenges or obstacles. The ability to persist through difficulties and find solutions can be valuable and highly sought after. Though there is also importance in knowing when to change tack if the problem is costing the developer/employee too much of their time. Many of the challenges or hurdles can be avoided or at least alleviated by developing problem-solving skills.
