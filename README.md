

  <p align="Left">
    <h1>Voronoi Stippling Site Header</h1> 
    <br />
    <a href="https://jcbbuller.github.io/voronoi_stippling_header/" target="blank">View Demo</a>
  </p>
  
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#download">Downloading The Files</a></li>
        <li><a href="#photos">Updating the Photos</a></li>
        <li><a href="#colors">Change the Colors</a></li>
        <li><a href="#resizing">Adjusting the Size</a></li>
      </ul>
    </li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot-main]](https://github.com/jcbbuller/voronoi_stippling_header/readme_examples/readme_example_main.jpg) 

I ran into this really cool dotted effect called <a href="https://observablehq.com/@mbostock/voronoi-stippling" target="_blank"> Voronoi Stippling while working as a Strategist in San Francisco. I really loved the artistic effect it makes and wanted to use it as a heaer on my own site. 

Once I got a pretty-good version of it up on my site, I made this repository so others can use or build something better with my code. You may suggest changes by forking this repo and creating a pull request or opening an issue. Thanks to all the people have contributed to expanding this template!

<br/><strong>Disclamir:</strong></br> I am NOT a developer. I have some front-end experience and visual design experience. Coding is a hobby for me so please be respectiful of my lack of skill/knowledge. 


### Built With

The project uses Bootstrap and the Voronoi Stippling technique.

Voronoi Stippling = [https://observablehq.com/@mbostock/voronoi-stippling]]


<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Download

I'm going to do write in a way that I wish someone would have written it to me when I 
was starting out. 

1. Go up to the green "code" button in the upper right and select "Download Zip".
2. Go to your computer's download folder and decompress the zip.
3. In there you will see the index file and assets needed to view the example in your favorite IDE.
   
### Photos

Based on my experience, this code likes very vivid, black and white photos. Experiement with high contrast photos with a lot of empty space - the dots will cluster to the darker, more vivid areas... I clearly know what I am talking about. 

Here is how to switch photos within the code.

1. Look for the "dottedheader_" javascript files within the "assets" folder.
3. On line 116 you'll see a file path to the image being used to create the design. You can change this path to whatever new image you want to use, or you can keep the same naming structure and just replace the image.
4. Each .js file has different file paths to different images. They are then linked to specific sections within the index.html and generate those individual designs in those sections. 


### Colors

Here is how to adjust the colors of the design within the code.

1. Look for the "dottedheader_" javascript files within the "assets" folder.
2. On line 9 and 17 you'll see hex codes for certain color swatches. If you plug in new hex codes here you can adjust what color is used for the background of the image and what color is used for the dots. I found that high contrasting colors work best.
   

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<strong>What I could use help with:</strong>
- Consolidation. There's a lot of loose/unused code in the plugin but I am a little too afraid to mess with it. 
- Mobility. Still having some issues with this. It looks like the Javascript assigned a pre-determined heigh and width to the image that could be the culpret.
- Load speed. On larger screens it can take a couple seconds for the stippling to show up in the header; this could just be the nature of the beast though. 

<!-- LICENSE -->
## License

Distributed under the Unlicense license. See `LICENSE.txt` for more information.


<!-- CONTACT -->
## Contact

Jacob Buller - [@jcbbuller](https://instagram/jcbbuller)

Project Link - [https://github.com/jcbbuller/voronoi_stippling_header](https://github.com/jcbbuller/voronoi_stippling_header)



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

I'm using this space to list resources I found helpful and would like to give credit to. 

* [Bootstrap v5.2](https://getbootstrap.com/docs/5.2/getting-started/introduction/)
* [Voronoi Stippling](https://observablehq.com/@mbostock/voronoi-stippling))

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/othneildrew/Best-README-Template/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/othneildrew/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/othneildrew/Best-README-Template/network/members
[stars-shield]: https://img.shields.io/github/stars/othneildrew/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/othneildrew/Best-README-Template/stargazers
[issues-shield]: https://img.shields.io/github/issues/othneildrew/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/othneildrew/Best-README-Template/issues
[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/othneildrew/Best-README-Template/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/othneildrew
[product-screenshot-main]: readme_example_images/readme_example_main.jpg
[product-screenshot-1]: readme_example_images/readme_example_1.jpg
[product-screenshot-2]: readme_example_images/readme_example_2.jpg
[product-screenshot-3]: readme_example_images/readme_example_3.jpg
[product-screenshot-4]: readme_example_images/readme_example_4.jpg
[product-screenshot-5]: readme_example_images/readme_example_5.jpg
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[Vorstip]: https://observablehq.com/@mbostock/voronoi-stippling
