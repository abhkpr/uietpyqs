# uietpyqs
## How can you upload PYQs?

I am going to explain it with a example, suppose i am a student of CSE-AI branch of batch 2023-27.
So right now, this is my 1st sem of 1st year and i want to add my 1st mid sem exam question paper

### Steps
1. Fork this repo.
2. Create a pdf file less than 2mb containing all subject papers of 1st mid sem exam.
3. ### Now naming  of pdf file is important-

**Name format= Entry year+Present year+Sem no.+X+Branch name.pdf**

    -- Entry year= 22 (for students right now in second year)
                   23 (for students right now in first year)

     -- Present year= 1 (for 1st year student)
                    = 2 (for 2nd year student)
                    = 3 (for 3rd year student)

     --Sem no.= 1 (for 1st sem)
              = 2 (for 2nd sem)
              = 3 (for 3rd sem)
              = 4 (for 4th sem)

      --X= 1 (1st mid sem)
           2 (2nd mid sem)
           3 (quiz)
           4 (end sem)

      --Branch name= it (for Information Technology)
                     cse (for Computer Science)
                     cseai (for Computer Science(AI))
                     ece (for Electronics and Communication)
                     che (for Chemical Engineering)
                     mee (for Mechanical Engineering)
So for the example taken above the pdf file name would be **23111cseai.pdf**

4. Add that or upload that pdf file to the folder 2023-27pdfs in your forked repo.
5. Now come to the file 2023-27_1st.html and go to the line ` <h2>CSE-AI</h2>`under that you can find the line
   `<h3>1 sem</h3>`under that`<li>1st mid sem</li>`
   change it to
`<li><a href="2023-27pdfs/23111.pdf">1st mid sem</a></li>` in your forked repo.
7. Now verify the changes and send a pull request....

### Notice:- These steps written for specific example(1st year CSE-AI student, who want to upload his 1st mid Que. paper of 1st sem), So make appropriate changes according to your condition.


