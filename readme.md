Vue How To:
(Kasih lihat demo jadinya dulu sebelum bikin dari template setengah jadi)

Vue Directive:
```
[] v-text 
[] v-html 

[x] v-if 
[] v-else  
[] v-else-if 
[x] v-show 

[x] v-on
[x] v-bind  
[x] v-model  

[x] v-for 
```

Step-by-step:
1. Masukkan VueJS ke index.html
2. Buat sebuah div dengan id app
3. Coba buat message hello vue dengan variabel {{ }}
4. Buat vue variabel dan message hello vue (isLoggedIn dan username)
5. v-if / v-show kan section 2, section 3, dan section 4
   - v-if section 2
   - v-if section 3
   - v-show section 4
6. v-if kan button Hello Someone
7. v-on:click kan untuk button Let's Go
8. v-on:click kan untuk button Hello, Someone
9. Tambahkan variabel todo dan todos (ambil dari db.json)
10. v-for the card, contohkan
11. Tambahkan form untuk addtodo
12. bungkus v-on:submit (alert saja)
13. ternyata refresh?
14. bungkus v-on:submit.prevent, (v-model dan logic)
15. Ternyata object keupdatenya ikutan binding data sebelumnya?
    (Ingat pass by references !)
16. Tambahkan Logic untuk finish Todo
17. Edit image, gunakan src dan alt nya sebagai bind
18. Tambahkan sebuah span di bawah identity dengan tulisan ini hanyalah tulisan merah,
    perbedaan antara v-html dan v-text

Referensi:
- https://vuejs.org/v2/guide/
- https://vuejs.org/v2/guide/events.html
- https://www.digitalocean.com/community/tutorials/vuejs-conditional-directives
- https://sweetalert2.github.io/#download