---
layout: default
---

## About Me

<img class="profile-picture" src="irene.jpg">

I am a Ph.D. student at [MIT CSAIL](https://www.csail.mit.edu/), working with [David Sontag](http://cs.nyu.edu/~dsontag/) in the [Clinical Machine Learning](http://clinicalml.org/) group. My research focuses on machine learning and its applications to solving important real-world problems including *healthcare* and *fairness*.

Prior to MIT, I worked at [Dropbox](www.dropbox.com) as Data Scientist, Chief of Staff, and Machine Learning Engineer. I graduated from [Harvard](https://www.seas.harvard.edu/) with a joint AB/SM in Applied Math and Computational Engineering where I researched with [Michael Luca](http://www.hbs.edu/faculty/Pages/profile.aspx?facId=602417) and [Ben Edelman](http://www.hbs.edu/faculty/Pages/profile.aspx?facId=417579).

You can email me at iychen [at] mit [dot] edu


## Research
Current research projects include

1. **Congestive Heart Failure**: How can we combine electronic health records with mechanistic information to better treat heart failure? What signal do echocardiograms contain? In collaboration with [Beth Israel Deaconess Medical Center](http://www.bidmc.org/).
2. **Health Knowledge Graph**: How can we build a structure to capture causal information on symptoms and diseases? Can we capture and quantify error in the model?
3. **Fairness in machine learning**: How can we make models that include people of all genders and races?


## Papers

1. **Why Is My Classifier Discriminatory?** Irene Chen, Fredrik D. Johansson, David Sontag. *Preprint.* [[arXiv]](https://arxiv.org/abs/1805.12002)
2. **Sources of Unfairness in Intensive Care Unit Mortality Scores.** Irene Chen, Fredrik D. Johansson, David Sontag. *Women in Machine Learning Workshop at NIPS 2017.*

## Teaching

At Harvard, I was awarded the [Derek Bok Center Certificate of Distinction in Teaching](https://bokcenter.harvard.edu/awards) for outstanding teaching evaluations.

I have served as a Teaching Fellow or Course Assistant for the following Harvard classes.

Year | Class Title | Professor
-----|-------|--------
2011 | Linear Algebra and Real Analysis I  | Paul Bamberg
2011 | Microeconomic Theory | Ed Glaeser
2012 | Linear Algebra and Real Analysis II | Paul Bamberg
2012 | Multivariable Calculus | Evelyn Hu, Avi Shapiro
2013 | Differential Equations | Margo Levine, Avi Shapiro
2014 | Algorithms and Data Structures | Michael Mitzenmacher

---

## Website credit

This is based on a [Jekyll](https://jekyllrb.com/) template. You can find the full source code on [GitHub](https://github.com/bk2dcradle/researcher).

<script type="text/javascript">
    //<![CDATA[
      $(document).ready(function(){

            $(".projDesc").hide();
            $(".projIconAndTitle").click(function(){
                $(this).next().next().slideToggle("fast");
                if ($(this).children().eq(0).html() == "-")
                    $(this).children().eq(0).html("+");
                else
                    $(this).children().eq(0).html("-");
            });

            $(".projIconAndTitle").hover(function(){
                $(this).toggleClass("activeTitle");
                $(this).children().eq(1).toggleClass("activeTitle");
            });

      });
    //]]>
    </script>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
        this.classList.toggle("active");
        var content = this.nextElementSibling;
        if (content.style.display === "block") {
            content.style.display = "none";
        } else {
            content.style.display = "block";
        }
    });
}
</script>
