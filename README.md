# ML-Credit-Scoring

Projekt składa się z trzech plików zawierających eksperymenty, oraz pliku głównego, który zawiera standardową wersję projektu.

Pierwszym eksperymentem jest sprawdzenie czy sposób przeszukiwania siatki hiperparametrów, Grid Search i Randomized Search, dla modeli uczenia maszynowego wpływa na wyniki modeli.
W głównym projekcie siatka hiperparametrów jest przeszukiwania w sposób losowy.
Ten eksperyment znajduje się w pliku "Grid Search".

Drugim eksperymentem jest sprawdzenie wpływu na wyniki użytego w projekcie procesowania danych. Eksperyment polega na zaniechaniu użycia syntezatora danych i jednocześnie zmianie rozkładu zmiennej celu na oryginalny rozkład, który jest wyraźnie niezbalansowany. Opisany eksperyment znajduje się w pliku "Procesowanie danych".

Trzecim eksperymentem jest sprawdzenie reakcji modeli na zmianę proporcji prób treningowej i testowej z 70/30 na 80/20.
Eksperyment znajduje się w pliku "Trening_Test".
