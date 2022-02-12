# CSCI 246, Spring 2022

This repository is created for part of the Spring 2022 Discrete Mathematics
(CSCI 246) course that is team taught by five faculty.  This repository contains
materials for the section taught by Prof. Brittany Terese Fasy.

Using git (and LaTex) is not required for this section of the class, but might
make completing the homework easier.  Compiled PDFs will be posted to the Google
Drive folder.

## Land Acknowledgement

Living in Montana, we are on the ancestral lands of American Indians, including
the 12 tribal nations that call Montana home today: A’aninin (Gros Ventre),
Amskapi/Piikani (Blackfeet), Annishinabe (Chippewa/Ojibway), Annishinabe/Métis
(Little Shell Chippewa), Apsáalooke (Crow), Ktunaxa/Ksanka (Kootenai), Lakota,
Dakota (Sioux), Nakoda (Assiniboine), Ne-i-yah-wahk (Plains Cree), Qíispé (Pend
d’Oreille), Seliš (Salish), and Tsétsêhéstâhese/So’taahe (Northern Cheyenne).
We honor and respect these tribal nations as we live, work, learn, and play in
this state.

To learn more about Montana Indians, I suggest starting with the following
pamphlet:
[Essential Understandings Regarding Montana
Indians](http://opi.mt.gov/Portals/182/Page%20Files/Indian%20Education/Indian%20Education%20101/essentialunderstandings.pdf)

## Important Class Resources

* [Google Drive
  folder](https://drive.google.com/drive/folders/15M83uQne8Y-jddRmr5QYIur-tM_K77VQ?usp=sharing)

## Creating Your Own Repository 

The repository is set as public, so you can access all course materials easily.
I suggest creating a private repository with this one setup as an upstream git
repo, so that you can use your repository to maintain your own materials for
this class. 

To do so, follow these instructions:
    
    - Going to <https://github.com/new>
    - Enter the name `csci-246-spring2022-private`
    - Select `Private`
    - **DO NOT ADD A README.MD or .gitignore!**

Once your repository is initialized, you can pull it down to your local machine.

Next, you should add the class repository as an upstream git repo:

```bash
$ git remote add upstream https://github.com/msu/csci-246-spring2022.git
$ git pull upstream main
$ git push
```
This will synchronize your private repository with the class repository.  You
only need to run these commands once.  Then, when you want to get an update from
the public class repository you can run this command:

```
$ git pull upstream main
```

As a general workflow on your own repository, I suggest:
```
$ git pull upstream master
[[ do work here ]]
$ git add [[ list filenames edited ]]
$ git commit -m "Descriptive message here"
$ git push origin main
`
