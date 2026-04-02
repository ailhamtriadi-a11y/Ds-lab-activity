Part 2 Warm-up Reflection
1. Why is numbers[2] very fast to access?
2. What happens if we want to insert 25 between 20 and 30?

Jawaban : 1. Karena Array langsung melompat menuju tujuan
yang membuatnya lebih susah ditambahkan karena fixed sedangkan linkedlist itu berurutan dari 
awal hingga akhir makanya lebih lama

2. Karena array itu berurutan ketika kita ingin menambahkan kita diharuskan
untuk memberikan ruang dan karena dicontoh tadi angka yang berada di belakang
25 adalah 30 dan 40 makanya bakal dimundurkan sebanyak 2 kali sebelum bisa dimasuskan

Part 6
3. If a node contains data = 15 and next = null, what does that tell us?

Expected idea:

It stores value 15
It is currently the last node in the list

Jawaban : 3. dikarenakan dibagian next = null ("null itu
itu memiliki artian tidak ada") maka dari itu
tidak bisa dilanjutkan karena alamat tidak tahu bakal dikemanakan

Part 8
4. Trace what happens if the list is empty and we call:

insertAtBeginning(100)

Jawaban : 4 Semisal kita memasuukan angka 100 sebagai angka baru
angka ini bakal dihitung dikarenakan Newmode.next = head dan head = newNode
jadi semisal walaupun dibagian head isinya kosong tetapi dikarenakan di newNode
itu sudah diisi dengan angka 100 maka ketika di run itu bakal menghasilkan angka 100


Part 15
p.A
5. Why does a linked list need a head variable?
6. Why does each node store a next reference?
7. Why is insertion at the beginning easier in linked list than in array?

Jawaban: 5. Dikarenakan head adalah satunya satunya tempat buat mendapatkan gambaran referensi
di list dan semisal kita kehilangan head maka node yang bakal tidak bisa dijalankan
dikarenakan tidak ada gambaran tentang apa yang harus dilakukan

6. Next dibutuhkan dikarenakan dalam linked list kita dibutuhkan berbagai arahan
agar suatu hal bisa dijalankan dan semisal next tidak ada maka linkedlist tidak punya
arahan terkait hal yang ingin dilakukan

7. Linkedlist lebih dimudahkan dibandingkan array karena ketika kita ingin memassukan
node yang baru kita hanya diperlukan untuk

p.b
8.  In insertAtBeginning(), why do we write:
    newNode.next = head;
    head = newNode;
    in that order?

9.  In display(), what would happen if we accidentally wrote:
    while (current.next != null)
    instead of:

    while (current != null)

Jawaban 8. karena kita bakal kehilangan newNode.next yang ingin dijadikan referensi oleh
Head yang karena itu membuat head kehilangan arah tentang apa yang bakal dilakukan selanjutkan
karena tidak memiliki akses ke sisa listnya lainnya

9. jika kita menulis tanpa menambahkan next maka program bakal berhenti sebelum mencetak node terakhir
dikarenakan penunjuk arahnya sudah tiada

p.C
10. Which structure is better for fast random access?
11. Which structure is better for frequent insertion at the beginning?
12. Why does linked list use more memory than array?

Jawaban : 10. Array Dikarenakan Array hanya mencari bagian tersebut aja agar bisa sampai ke tujuan
sedangkan linkedlist harus dikunjungi satu persatu elemen yang dicari sebelum sampai ke tujuan 

11. Linkedlist dikarenakan array semisal ada angka yang ingin dimasukkan maka angka yang dibelakangnya
juga harus mundur yang dimana tidak sebagus linkedlist dikarenan mereka itu tinggal mengubah referensi aja 


12. karena hanya disuruh dimassukan data sedangkan kalau linked list selain data juga harus dimasukkan 
alamat agar bisa menuju ke node selanjutnya
