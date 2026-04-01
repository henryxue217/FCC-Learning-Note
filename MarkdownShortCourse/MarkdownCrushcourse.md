# Markdown Crash Course and Checksheet  
  link on the page : `LinkName](#Heading-name)` if there are spaces in btween heading name, you must use - to replace space. 
  `[Heading 6](#heading-6)`
  [Heading 6](#heading-6)
  
## Source:
Yotube Video: [Learn Mardown In 22 Minitues](https://www.youtube.com/watch?v=_PPWWRV6gbA&t)  
Blog: [Markdown Crash Course Blog](https://blog.webdevsimplified.com/2023-06/markdown-crash-course/)

### Markdown CheetSheet - All you need  
* `  `: two space means new line br as `<br>` in html
  * space at the beginning of of line and the end of line matters. 
* \#: `# Heading size 1`
  # Heading 1
* \##: `## Heading size 2`
  ## Heading 2
* \###: `### Heading size 3`
  ### Heading 3
* \####: `#### Heading size 4`
  #### Heading 4
* \#####: `##### Heading size 5`
  ##### Heading 5
* \######: `###### Heading size 6`
  ###### Heading 6 
* **Blod**: `**Bold**`
* *Italics*: `*Italics*`
* ***Blod and Italics***: `***Bold and Italics***`
* ~~Crossed Off~~: `~~Crossed Off~~`
* ==highlight==: (does not work in github)
  * <mark>highlight</mark>: `<mark>highlight</mark>`
* ^superscript^: (does not work in github)
  * 2<sup>2</sup>=4: `2<sup>2</sup>=4`
* \~suberscript\~: (does not work in github)
  * H<sub>2</sub>O: `H<sub>2</sub>O`
* \`single line code\` 
* \```Multi-line code\```  
  * \```JS  
     console.log("Javascript");  
     console.log("Javascript");  
    \```
     ```JS
       console.log("Javascript");
       console.log("Javascript");
     ``` 
* \[This is a local link\]\(\/localpage\)
    * \[Link to README.md\]\(\/README.md\)  
      [Link to README.md](/README.md)
      (https:\\google.com)
* \!\[image\]\(image link\): link image  
   * `![freecodelogo](https://design-style-guide.freecodecamp.org/downloads/fcc_secondary_large.png)`
    ![freecodelogo](https://design-style-guide.freecodecamp.org/downloads/fcc_secondary_large.png)

* block quote syntax
  * ```MD
    > a
    > > b
    > > > c
    ```
    > a
    > > b
    > > > c
* create a horizontal line: either one of them works 
  ```md
    ***
    ---
    ___
  ```
   ***
   ---
   ___
* order list
  ```md
    1. Item 1
    2. Item 2
    3. Item 3
  ```
    1. Item 1
    2. Item 2
    3. Item 3
  * unorder list: ethier one of these symbol works 
    ```md
      -
      *
      +
    ```
      - item 1
      - item 2
      - item 3
  * nested unorder or ordere list:
    ```md
        - item 1
          - item 1-1
          - item 1-2
            1. item 1-1.1
            2. item 1-2.2
        - item 2
    ```
      - item 1
          - item 1-1
          - item 1-2
            1. item 1-1.1
            2. item 1-2.2
       - item 2
    * creat a table
      ```md
        |Header1| Header2 |
        |------- | ------|
        | Your name| My Name|
      ```
       |Header1| Header2 |
        |------- | ------|
        | Your name| My Name|
        * `|:---|` : make the col left align
        * `|----:|`: make the col right align
        * `|:---:|`: make the col center align
    * [ ] | [x]: check box 
         
