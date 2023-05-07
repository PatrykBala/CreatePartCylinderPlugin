# Create Part Cylinder Plugin to Abaqus.
## General info
The script is equipped with a graphical user interface that allows you to automatically draw a selected shape based on the given dimensions, and then save the created element to a file. A script that draws a ring with user-specified dimensions: A (ring height), B (ring diameter) and C (wall thickness).

Graphical user interface equipped with a form, where the user provides selected dimensions of the drawn element, and also selects the file format. Validation of the entered data. If a dimension is incorrect or drawing a shape with the given dimensions is impossible, the script should display an appropriate message to the user. The script allows you to save up to three formats: .step, .igs and .sat

<sub> PL: Skrypt wyposażony w graficzny interfejs użytkownika, który pozwala na zautomatyzowane rysowanie wybranego kształtu na podstawie podanych wymiarów, a następnie zapis stworzonego elementu do pliku. Skrypt rysujący pierścień o podanych przez użytkownika wymiarach: A (wysokość pierścienia), B (średnica pierścienia) i C (grubość ścianki). </sub>

<sub> Graficzny interfejs użytkownika wyposażony w formularz, gdzie użytkownik poda wybrane wymiary rysowanego elementu, a także wybierze format zapisu pliku
Walidacja wprowadzonych danych. Jeśli jakiś wymiar jest nieprawidłowy lub narysowanie kształtu o podanych wymiarach jest niemożliwe, skrypt powinien wyświetlić odpowiedni komunikat użytkownikowi
Skrypt umożliwia zapis do trzech formatów: .step, .igs i .sat </sub>

## Technologies
Solidworks macro as *.swp* file.

## Setup
1. **Start** *Solidworks*.
2. **Run** the macro options.
3. **Locate** the *CreateRing.swp* file and **open**.
4. **Enter** the ring data.
5. After entering the data, click **Run**.
6. A ring with the dimensions you specified will be created.
