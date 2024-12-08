# Walkthrough / Solutions (Spoilers!)

Below is how you would solve the challenge for each provided image. Organizers can reveal this file after the challenge or keep it separate.

## General Method:
1. Use `exiftool` or a similar tool to extract metadata from the provided image(s):
   
   ```bash
   exiftool image.jpg
   ```
2.  Identify the GPS coordinates in the metadata output. You might see:

    ```bash
    GPS Coordinates:  XX.xxxx° N, YY.yyyy° W 
    ```

3.  Input these coordinates into a mapping service (Google Maps, Bing Maps, OpenStreetMap, etc.).

4.  Identify the landmark or location displayed at those coordinates.

Specific Solutions:
-------------------

### Image 1\. Kilchurn Castle, Loch Awe, Argyll, Scotland

-   **Approximate Coordinates:** 56.4039° N, 5.0297° W
-   **Method:** After extracting these coordinates and searching on a map, you'll find Kilchurn Castle on the banks of Loch Awe in Argyll, Scotland. The image might show a castle ruin's reflection on calm water, a hint that it's a historical Scottish castle location.

### Image 2\. Male White Rhinoceroses at Lake Nakuru, Kenya

-   **Approximate Coordinates:** 0.3800° S, 36.0932° E
-   **Method:** Extracting the coordinates and placing them on a map reveals Lake Nakuru National Park in Kenya. The presence of white rhinos should confirm you are looking at an African wildlife reserve.

### Image 3\. Old Town in Helsinki, Finland

-   **Approximate Coordinates:** 60.1699° N, 24.9524° E
-   **Method:** The coordinates lead you to Vanhakaupunki, literally translated as Old Town, in Helsinki, Finland. Confirming these coordinates on a map pinpoints the historic center of Helsinki.

### Image 4\. Pearl Harbor Memorial Bridge, New Haven, Connecticut, USA

-   **Approximate Coordinates:** 41.2989° N, 72.9122° W
-   **Method:** Inputting these coordinates directs you to New Haven, Connecticut. The image, showing part of a modern bridge structure, corresponds to the Pearl Harbor Memorial Bridge along Interstate 95. It is locally known as Q Bridge.

* * * * *

**Remember:**

-   The key step is extracting the GPS data from the image metadata and using those coordinates rather than guessing visually.
-   If multiple images are provided, solve each one in the same manner. The challenge trains the student's ability to interpret metadata, use mapping tools, and reason about geography.