## Exercise 1
### Number 1
Writing in Markdown is _not_ that hard!

### Number 2
I **will** complete these lessons!

### Number 3
"_Of course_," she whispered. Then, she shouted: "All I need is **a little moxie**!"

### Number 4
If you're thinking to yourself, **_This is unbelievable_**, you'd probably be right.

### Number 5
# Header one
## Header two
### Header three
#### Header four
##### Header five
###### Header six

### Number 6
#### Colombian Symbolism in _One Hundred Years of Solitude_
Here's some words about the book _One Hundred Years..._.

### Number 7
[Search for it.](www.google.com)

### Number 8
[You're **really, really** going to want to see this.](www.dailykitten.com)

### Number 9
#### The Latest News from [the BBC](www.bbc.com/news)

### Number 10

Do you want to see [something fun][a fun place]?  
Well, do I have the [website for you][another fun place]!  

[a fun place]: www.zombo.com  
[another fun place]: www.stumbleupon.com  

### Number 11
![A pretty tiger](https://upload.wikimedia.org/wikipedia/commons/5/56/Tiger.50.jpg)

### Number 12  

![Black cat][Black]

![Orange cat][Orange]

[Black]: https://upload.wikimedia.org/wikipedia/commons/a/a3/81_INF_DIV_SSI.jpg

[Orange]: https://icons.iconarchive.com/icons/google/noto-emoji-animals-nature/256/22221-cat-icon.png


### Number 13
I read this interesting quote the other day:
>"Her eyes had called him and his soul had leaped at the call. To live, to err, to fall, to triumph, to recreate life out of life!"

>Once upon a time and a very good time it was there was a moocow coming down along the road and this moocow that was coming down along the road met a nicens little boy named baby tuckoo...
>
>His father told him that story: his father looked at him through a glass: he had a hairy face.
>
>He was baby tuckoo. The moocow came down the road where Betty Byrne lived: she sold lemon platt.

### Number 14
>He left her quickly, fearing that her intimacy might turn to jibing and wishing to be out of the way before she offered her ware to another, a tourist from England or a student of Trinity. Grafton Street, along which he walked, prolonged that moment of discouraged poverty. In the roadway at the head of the street a slab was set to the memory of Wolfe Tone and he remembered having been present with his father at its laying. He remembered with bitterness that scene of tawdry tribute. There were four French delegates in a brake and one, a plump smiling young man, held, wedged on a stick, a card on which were printed the words: _VIVE L'IRLANDE_!

### Number 15
* Flour
* Cheese
* Tomatoes

### Number 16
1. Cut the cheese
2. Slice the tomatoes
3. Rub the tomatoes in flour

### Number 17
* Azalea (_Ericaceae Rhododendron_)
* Chrysanthemum (_Anthemideae Chrysanthemum_)
* Dahlia (_Coreopsideae Dahlia_)

### Number 18
* Calculus
  * A professor
  * Has no hair
  * Often wears green
* Castafiore
  * An opera singer
  * Has white hair
  * Is possibly mentally unwell

### Number 19
1. Cut the cheese  
Make sure that the cheese is cut into little triangles.

2. Slice the tomatoes  
Be careful when holding the knife.  
For more help on tomato slicing, see Thomas Jefferson's seminal essay _Tom Ate Those_.

### Number 20
We pictured the meek mild creatures where  
They dwelt in their strawy pen,  
Nor did it occur to one of us there  
To doubt they were kneeling then.  

### Number 21
1. Crack three eggs over a bowl.  
 Now, you're going to want to crack the eggs in such a way that you don't make a mess.   
If you _do_ make a mess, use a towel to clean it up!

2. Pour a gallon of milk into the bowl.  
 Basically, take the same guidance as above: don't be messy, but if you are, clean it up!

## Exercise 2

### 5 facts about **troff**
1. troff is short for "typesetter roff". It is the major component of a document processing system developed by Bell Labs for the Unix operating system. troff and the related nroff were both developed from the original roff.
2. troff features commands to designate fonts, spacing, paragraphs, margins, footnotes and more. Unlike many other text formatters, troff can position characters arbitrarily on a page, even overlapping them, and has a fully programmable input language. Separate preprocessors are used for more convenient production of tables, diagrams, and mathematics. 
3. Inputs to troff are plain text files that can be created by any text editor.
4. Troff was originally written by the late Joe Ossanna in about 1973.
5. While troff has been supplanted by other programs such as Interleaf, FrameMaker, and LaTeX, it is still being used quite extensively. It remains the default formatter for the UNIX documentation.

Visit [Wikipedia](https://en.wikipedia.org/wiki/Troff) and [troff](https://troff.org/) for more facts!

### 5 facts about **Scribe**

1. Scribe is a markup language and word processing system.
2. Scribe was designed and developed by Brian Reid of Carnegie Mellon University. It formed the subject of his 1980 doctoral dissertation. 
3. Scribe contained the first robust implementation of declarative markup language.
4. Using Scribe involved a two phase process:  
  * Typing a manuscript file using any text editor, conforming to the Scribe markup.
  * Processing this file through the Scribe compiler to generate an associated document file, which can be printed.
5. Because of the separation between the content (structure) of the document, and its style (format), writers did not need to concern themselves with the details of formatting.

[Scribenet](https://scribenet.com/wfdw/docs/scml.html) Provides good examples of the structure.


## Exercise 3

Here is a video of funny cats:


[![funny cats](https://www.gstatic.com/youtube/img/branding/youtubelogo/svg/youtubelogo.svg)](https://www.youtube.com/watch?v=DHfRfU3XUEo)



Here is my favourite animal in the world:


![Snowleopard](https://static.wikia.nocookie.net/animals-are-cool/images/a/ad/SnowLeopard.jpg/revision/latest/scale-to-width-down/1000?cb=20180802215804)




## Exercise 4

```
public class Person
{
  private string name;
  private int age;

  public Person(string initialName)
  {
    this.age = 0;
    this.name = initialName;
  }
  public void PrintPerson()
  {
    Console.WriteLine(this.name + ", age " + this.age + " years");
  }
  public void GrowOlder()
  {
    this.age = this.age + 1;
  }
}
```