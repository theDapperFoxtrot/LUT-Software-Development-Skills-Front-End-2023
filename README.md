# Software-Development-Skills-Front-End-2023

Showcase of my working project here: https://www.youtube.com/live/HNirdqHrUjQ
I used a separate repo for my project submission because it is a project I will continue to improve on beyond this course, as it serves a real business in Helsinki.
The project submission: https://github.com/theDapperFoxtrot/lloyds-cafe
You can find it hosted at: https://lloydscafe.netlify.app/

## Learning Diary

Date May 24th, 2023

I've been a little busy with starting my business, but I finally got a minimum viable product created for my project submission to complete this course. My final thoughts and description of the project are in this YouTube video: https://www.youtube.com/live/HNirdqHrUjQ

Date: May 10th, 2023

Today was a productive day of learning as I delved into the world of web development. I started by setting up my coding environment, which was not unfamiliar territory, but I appreciated the link to discover a couple of new extensions in VS Code I found useful. I got everything up and running smoothly.

Next, I began reminding myself about Sass, but I was shocked by the video when I saw Traversy Media setting up Node-Sass manually. I've always used the Live Sass Compiler extension in VS Code, and I appreciated the insight on how I could set up the compiler manually. I'll appreciate the practice, as for the most part my experience with Sass has been using it as a means of organizing pieces of styling in partials.

So I'm continuing my journey to becoming a web developer. I feel more confident in my ability to set up a development environment, and use Sass to write more efficient CSS. I look forward to continuing to learn and grow in this exciting field.

Date: May 13th, 2023

The other day, (May 11th) I worked on creating the homepage for the tutorial project. I started by writing the HTML markup for the page, using semantic elements to structure the content.

Next, I moved on to creating the core Sass/CSS for the project. Some variables for colors, fonts, and other styles recommended by Traversy Media. However, I took some liberties, because I've always embraced a mobile-first design philosophy, and therefore I always prioritize making things look good on mobile. I always open my dev tools and work with a 320px width in my viewport to account for the Nokia Lumia 520 (a model of phone). While there may be some phones that have an even smaller width, it's a very uncommon outlier that I have decided isn't worth the effort.

One of the things I was reminded of about Sass was its support for nesting. This allowed me to group related styles together and made my code much more readable and organized. For example, I could write something like:

```
header {
  background-color: $primary-color;

  nav {
    display: flex;
    justify-content: space-between;
    align-items: center;

    a {
      color: $white;
      font-weight: bold;
      text-decoration: none;
    }
  }
}
```

This made it clear which styles were being applied to which elements, and also made it easy to make changes later on if necessary. I was well aware of partials, and actively used them, but this is a further helpful way to organize the work and make it reader-friendly.

Overall, I'm really pleased with how the homepage is coming along, and I'm looking forward to getting more practice with animations to create what people call a more modern website. I'm somewhat anti-animations, but I know that they're necessary to please audiences at times. Personally, I think animations only serve a specific audience, and I'd rather put more emphasis on catoring to accessibility needs than flashy graphics.

Today I move on to Part 3.

Edit: I forgot to mention, Traversy Media was teaching people to set up a 'manual' way of refreshing the page while using Sass, but I prefer to use the VS Code extension to simplify the process. It auto creates the necessary files with one click. It was really nice to see how the extension is working under the hood though.

Date: May 16th, 2023

I had to take a short break from the course to deal with work. Now I have a lot more time to dedicate to my studies and review so much material. This Traversy Media tutorial is a great reminder of the power behind using SASS, and I'm enjoying rediscovering a lot of properties I hadn't used for many months. Like any language - use it or lose it!

Onto Part 4.

It was very nice to reacquaint myself with the sorts of styling animations that I have long avoided. When you find yourself to not be very artistic, and care more about programming the functionality of an app, you tend to really appreciate when someone can demonstrate some interesting possibilities you might never have thought of on your own.

I was especially impressed by the for loop used in SASS to create an interesting effect with the menu loading in.

Date: May 17th, 2023

There's so many properties, let alone functionality in sass, that exist. It's a wonder if and when a developer will even use them. The majority of my styling has been very flex-centric, but now I'm getting some practical usage with grid. Even when I used grid, I hadn't heard of template areas as a way to make a scheme for placing elements on a page. I'm sure it gets much more advanced, but I'm even impressed with the simple example in this tutorial.

End of part 5.

Date: May 19th, 2023

I completed the Traversy Media tutorial. I already had an awareness of how to host a site on both Netlify and using Github Pages, but it was a nice review. The one thing I'm a bit unclear about is hosting multiple directories using Github Pages. For the sake of making navigating to the tutorial project easier, I've removed the original folders I had (Coureswork/Part1), because I didn't end up breaking each part into separate branches.

For my project, I'd like to apply the skills practiced in the tutorial and make a website for a local cafe. This makes the project practical, and gives me incentive to focus on quality of the finished product. I'm not sure if that deviates too much from the course expectations or not, but I'm hoping that it will be welcome, since it will show that I can build something using the skills and not copying the foundation of the tutorial and simply editing it.

I will make a separate repo for it, and then explain how to access it in this readme at the top. Maybe I'll add a link to the cafe site as well via the tutorial project, just to ensure it isn't missed.

Date: May 22nd, 2023

After some futher consideration, the complexity (or lack thereof) of this site doesn't necessitate using the React library. It's creating unnecessary snags in deployment, and while I could keep grinding away to overcome it, the payoff versus making a site with Vanilla JS is zero.

I'm going to create it the imperative way in the interest of time. Since I have courses starting soon, and I would like to submit this project and have the course graded.
