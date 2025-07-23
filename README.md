# PING-PONG-
Proiectul "Ping Pong" simulează un joc de ping pong folosind o serie de LED-uri și două butoane de control. Jocul este inițializat cu LED-ul 15 aprins. Utilizatorul 1 activează jocul prin apăsarea butonului btnL, declanșând o secvență de aprindere a LED-urilor (de la LED 15 la LED 0) ce simbolizează o "servă". Utilizatorul 2 trebuie să reacționeze exact când LED 0 este aprins, astfel "returnând mingea". Dacă acțiunea este corectă, secvența LED-urilor se inversează (de la LED 0 la LED 15), iar jocul continuă prin alternanța utilizatorilor.
În cazul în care unul dintre jucători ratează momentul, toate LED-urile se aprind pentru o secundă, se incrementează scorul, iar LED-ul 15 se reaprinde ca punct de start pentru următoarea rundă. Scorul fiecărui jucător este afișat pe un display cu 4 cifre, primele două cifre indicând scorul utilizatorului 1, iar următoarele două pentru utilizatorul 2. Pe măsură ce se succed schimburile de minge fără erori, viteza jocului crește progresiv, sporind dificultatea.
Tehnologii și componente utilizate:
Microcontroler (în funcție de implementare hardware specifică)
LED-uri pentru reprezentarea vizuală a "mingii"
Butoane btnL și btnR pentru interacțiunea utilizatorilor
Afișaj cu 4 cifre pentru scor
Aspecte remarcabile ale proiectului
Interactivitate: Experiența jocului este asigurată de sincronizarea precisă între LED-uri și apăsările de buton, simulând realitatea unui meci de ping pong.
Dinamică de joc: Viteza jocului crește treptat în funcție de succesul schimburilor de minge, ceea ce crește gradul de dificultate și implicarea jucătorilor.
Feedback vizual: Schimbările de stare (de ex., atunci când un jucător ratează mingea) sunt comunicate imediat prin aprinderea simultană a tuturor LED-urilor, oferind un feedback clar și intuitiv.
Ce am învățat / realizat:
Implementarea unei logici secvențiale și a unor mecanisme de detecție a evenimentelor în timp real.
Sincronizarea între componente hardware (LED-uri, butoane, afișaj) pentru a crea o experiență de joc coerentă.
Optimizarea codului pentru a permite o creștere progresivă a vitezei, ceea ce a implicat o gestionare eficientă a timpilor de întârziere și a resurselor procesorului.
