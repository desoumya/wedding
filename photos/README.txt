OUR MEMORIES — how to add your photos
=====================================

1. Drop your images into THIS folder, named:

       1.jpg   2.jpg   3.jpg   4.jpg   5.jpg   6.jpg

   Those are the six filenames index.html already looks for.
   Any slot with no file shows a dashed frame naming the file
   it is waiting for — so you can always see what is missing.

2. Want more or fewer than six, or different names?
   Open index.html, find the "photos:" list inside the CONFIG
   block near the top of the <script>, and edit it:

       photos: [
         { src:'photos/beach.jpg', caption:'Goa, 2024' },
         { src:'photos/2.jpg',     caption:'' }
       ]

   Leave caption as '' if you don't want text on the photo.

3. Two things that matter for guests on mobile data:

   SIZE    Keep each file under about 500 KB. A photo straight
           off a phone is 3-6 MB and will make the page crawl.
           Resize the long edge to ~1200px before saving.

   SHAPE   Portrait photos (taller than wide, roughly 3:4) fill
           the frame best. Landscape photos still work — they
           get cropped to the centre.

4. Filenames are case-sensitive on most web hosts.
   'photos/1.JPG' and 'photos/1.jpg' are NOT the same file.
   Stick to lowercase and you'll never hit this.
