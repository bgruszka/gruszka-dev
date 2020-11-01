---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Ana Language"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2020-06-19T16:51:29+02:00
lastmod: 2020-06-19T16:51:29+02:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
Nowy język programowania.

Założenia:
* napisany w C++
* gramatyka generowana przy pomocy ANTL
* jest językiem obiektowym
* bloki w {}
* ma wbudowany GC
* listy []
* tylko petle for (brak while)
* slicing tablic i stringow
  
zmienna := 10;

for(i:=0; i<10; i++) {
  if(i % 2 == 0) {
    zmienna++;
  } else (i % 3 == 0) {
    zmienna--;
  } else {
    zmiennab := toJakasFunkcja(i)
  }
}

create topic1[replicaset:1, ]