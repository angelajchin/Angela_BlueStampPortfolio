# Floor Cleaning Robot
Cleaning your floor has never been easier! This floor-cleaning robot works autonomously by avoiding nearby obstacles using ultrasonic and infrared sensors. The brush attached to its underside sweeps up any debris it encounters while moving. 

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Angela C. | Diamond Bar High School | Biosystems Engineering | Incoming Junior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
<!---# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone -->

# First Milestone
<iframe width="953" height="438" src="https://www.youtube.com/embed/IzxStotfcVk" title="Angela C. Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

My first milestone was finishing the hardware portion of my base project. This was relatively simple, as the floor cleaning robot is essentially a standard 3-in-1 starter kit robot. The chassis of this bot is made from an acrylic board, two TT wheels, and one universal wheel. Attached to it is an Arduino Uno R3 board acting as the "brain" of the bot, controlling the TT motors. The ultrasonic sensor emits sound pulses to measure the distance to an object in front of it, while the IR sensors sense any obstructions to the right and left of the robot. My only issue was that the wheels occasionally dragged when turning, but I chalked it up to the them getting caught on the acrylic board.

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| 3 in 1 Starter Kit | All components of the robot can be found within the starter kit, including the chassis. | $69.99 | <a href="https://www.sunfounder.com/products/sunfounder-3-in-1-iot-smart-car-learning-ultimate-starter-kit"> Link </a> |
| Odistar Desktop Vacuum Cleaner | For cleaning the floor | $12.98 | <a href="https://www.amazon.com/ODISTAR-Endurance-Cordless-Rotatable-Keyboard/dp/B07Q128V6W/ref=sr_1_1_sspa?crid=GTU49YHVDQWH&dib=eyJ2IjoiMSJ9.7-jDIbAMj99apdM_o_tLpsiMU6__WeFo0jVnuZp4HXX5tHOHRXb66kw-HGzvDadVS5x0-_yRjqsAvIwupdlePsQBvta8EnoEUn-bV8riLfrQDSmc8oA7QwR0_bv7PFhzW9HCeLLtlY2HeyKwOcJYCkptrZhRWCsIRB6hi3mIM8mELFfRgPnJnAAojT23QOLDN_ojzKNDCWpzrbnlPaHWyCVKXGk6DI1i-PdmSrluJlg.5YwF74G0MfllQsEfLe-Ntj9BZGB_MJ5HbVqeb2vmbzI&dib_tag=se&keywords=odistar%2Bdesk%2Bvacuum&qid=1781204100&sprefix=odistar%2Bdesk%2B%2Caps%2C160&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)
