## Generowanie grafik
Początkowo na własne potrzeby zaprojektowałem mikroserwis, który generuje zoptymalizowane kreacje na podstawie specjalnego szablonu. Później projekt został rozszerzony o moduł w [[Integromat]] oraz teraz jest dostępny dla innych pod nazwą [[EasyBanner]].

Z jego pomocą jestem w stanie tworzyć setki grafik w ciągu kilku minut, przesyłając np. dane z [[Airtable]] lub nawet bezpośrednio z mojego komputera (z pomocą [[Keyboard Maestro]]).

Poza tworzeniem grafik na podstawie szablonu HTML, możliwe jest też generowanie ich na podstawie projektu [[Webflow]], który po udostępnieniu zostaje przekazany do [[EasyBanner]]. 

## Licznik na stronę i e-mail
W kampaniach wykorzystuję liczniki odmierzające czas do zakończenia sprzedaży lub promocji. Początkowo wykorzystywałem sendtric.com do generowania prostego licznika, jednak potrzebowałem mieć nad nim większą kontrolę i dostosowac go do swoich potrzeb. 

Tak powstał mikroserwis umożliwiający generowanie timerów w formie pliku .gif. Aktualnie dostępny jest jako [[EasyTimer]]

## Carbon.now.sh
Prosty mikroserwis do którego mogę przesłać ID gista i na jego podstawie zostanie wygenerowana grafika z odpowiednio sformatowanym fragmentem kodu.

## $AHOY
Mikroserwis symulujący blockchain, umożliwiający zapisywanie historii transakcji, tworzenie portfeli i ich kategorii. 
