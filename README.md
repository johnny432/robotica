  Descriere tema

  În această temă trebuie să simulați o stație de încărcare pentru un vehicul electric, folosind mai multe LED-uri și butoane. În cadrul acestui task trebuie să țineți cont de stările butonului și să folosiți debouncing, dar și să coordonați toate componentele ca într-un scenariu din viața reală.

  Cerinte tema
   Led-ul RGB reprezintă disponibilitatea stației. Dacă stația este liberă led-ul va fi verde, iar dacă stația este ocupată se va face roșu.

   Led-urile simple reprezintă gradul de încărcare al bateriei, pe care îl vom simula printr-un loader progresiv (L1 = 25%, L2 = 50%, L3 = 75%, L4 = 100%). Loader-ul se încărca prin aprinderea succesivă a led-urilor, la un interval fix de 3s. LED-ul care semnifică procentul curent de încărcare va avea starea de clipire, LED-urile din urma lui fiind aprinse continuu, iar celelalte stinse.

   Apăsarea scurtă a butonului de start va porni încărcarea. Apăsarea acestui buton în timpul încărcării nu va face nimic.

   Apăsarea lungă a butonului de stop va opri încărcarea forțat și va reseta stația la starea liberă. Apăsarea acestui buton cat timp stația este liberă nu va face nimic.

  Componente
    4x LED-uri (pentru a simula procentul de încărcare)
    1x LED RGB (pentru starea de liber sau ocupat)
    2x Butoane (pentru start încărcare și stop încărcare)
    8x Rezistoare (6x 220/330ohm, 2x 1K)
    Breadboard
    Linii de legătură


![WhatsApp Image 2024-10-22 at 22 41 03](https://github.com/user-attachments/assets/557600cb-0397-4ed3-85ce-18514394574a)

    


https://github.com/user-attachments/assets/ff501e72-ef03-475a-86c4-8cafee6475f5


![Bodacious Jaiks-Hango](https://github.com/user-attachments/assets/bed4607a-d162-4b91-abf3-b375f04fa292)


    
