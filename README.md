# Mathdown background
As a math enthusiast, handwritten notebooks are a great way to organize thoughts and record inspirations, but poor handwriting makes this experience thoroughly frustrating.  

When working through calculations, numbers are crooked and symbols are blurred, leaving me fearing that misreading a character will disrupt the logical flow of my deductions.  

When organizing formulas and theorems, I try to write each step clearly and systematically, but messy handwriting jumbles the formulas together, and highlighted key points look chaotic. Good mathematical knowledge ends up obscured by sloppy writing, making it incomprehensible. I not only fail to enjoy the neat beauty of notes but also feel a sense of frustration due to bad handwriting, greatly reducing the practical value of handwritten notes.  

- Using Word for math notes makes editing formulas a real "torture."  
  On one hand, you have to constantly switch between the mouse, Word, and the formula editor—jumping between interfaces repeatedly just to write one formula, which often interrupts your thinking.  
  On the other hand, as a heavyweight software, Word has numerous redundant features and complicated formatting settings. Adjusting line spacing, aligning formulas, setting fonts, and other formatting tasks take up a lot of time. These unnecessary formatting hassles divert energy away from the math itself and waste it on irrelevant software operations, resulting in extremely low efficiency.  

- Although Markdown is lightweight, its experience when editing math formulas is equally poor.  
  Firstly, you have to repeatedly switch between "content editing" and "preview" modes. You can’t see the final effect while writing a formula, and after previewing and finding issues, you have to go back to edit—this back-and-forth disrupts the thinking rhythm.  
  Secondly, formulas must be written using LaTeX source code. A bunch of complex symbolic code clutters the text, which is not only dazzling to look at but also tedious to memorize various syntax rules and debug. Energy that should be focused on mathematical deduction is scattered on source code, greatly reducing note-taking efficiency.  

I truly want a math note-taking software like this: simple to operate, no need to worry about formatting, no need to get stuck messing around with LaTeX source code, and no need to deal with unnecessarily complicated formatting settings. I just want to focus all my energy on formula input itself—being able to directly click and modify written formulas for real-time editing. Additionally, the formula auto-completion feature should be rich enough, popping up options when I type half a symbol, allowing me to write formulas as casually and naturally as having a chat.  

But the reality is disappointing: today’s technology is clearly incredibly advanced. AI shows off all kinds of tricks—writing articles, drawing pictures, and even rockets landing on the moon time and time again to explore the unknowns of the universe. Yet, surprisingly, the experience of editing math formulas that we use every day still remains in a backward stage. Either you have to remember a bunch of complex syntax rules, or you have to switch repeatedly between multiple interfaces and modes, or the auto-completion feature is practically useless. Writing a simple formula casually takes a lot of effort. The feeling of being stumped by a small formula editing task while living in a high-tech era is really frustrating.  

Looking through the numerous note-taking and editing software available on the market, it’s hard to find one that truly meets these needs. Some hide complex formatting settings, forcing people to spend energy on formatting; some can’t input formulas without LaTeX source code, requiring memorizing syntax and checking manuals just to write a symbol; some have real-time editing and auto-completion features that are practically non-existent, making you re-enter the entire formula when you want to modify it and offering no help when you want to save time; others have convoluted operational logic, completely lacking the ease of "writing casually and modifying easily." These software either neglect some needs while addressing others, or overcomplicate simple formula input. They always fail to allow people to completely put aside distractions and focus solely on the deduction and recording of math itself.
Based on this, I decided to roll up my sleeves and create one myself. Building on Markdown syntax and integrating real-time math formula editing, Mathdown was thus born.

# Mathdown Introduction
It is a personal knowledge system focusing on mathematical formula editing. As the world's first Markdown software that supports real-time editing of mathematical formulas, it delivers a smooth formula editing experience.

# Why is the experience described as "smooth"?  
- Real-time editing directly on formulas—no more switching back and forth between source code and preview.  
- A rewritten cursor system that makes editing formula blocks identical to editing plain text, allowing you to keep your hands on the keyboard at all times.  
- Pinyin completion, command completion, custom completion, and expression completion.  
- Bidirectional links and an automatically navigable tag system, ensuring no piece of knowledge remains an isolated island.
