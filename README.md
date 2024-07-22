GlyphsApp Feature: CCMP
-----
Update made in 2024-07-22
# GSUB Lookup Type 4 – ligature substitution
Swaped position started with set of tone-mark first then `nikhahit-thai`
This way, it will work on both Desktop and also Canva 
```
lookup ccmp_thai_nikhahit_normal {
	sub maiEk-thai nikhahit-thai by nikhahit_maiEk-thai;
	sub maiTho-thai nikhahit-thai by nikhahit_maiTho-thai;
	sub maiTri-thai nikhahit-thai by nikhahit_maiTri-thai;
	sub maiChattawa-thai nikhahit-thai by nikhahit_maiChattawa-thai;
} ccmp_thai_nikhahit_normal;
```
Loop: 
**Update 2024-07-22**  
My current Thai Loop feature file has the additional glyph.left tone-mark to prevent tone-mark crash with `ใ ไ โ`set 

Loopless: 
**Update 2024-07-22**
