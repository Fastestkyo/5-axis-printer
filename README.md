# 5-axis printer

this is a personal project where im building a 5-axis 3d printer, inspired by multipole’s 5-axis design. after i make the printer, i will try to add a mmu to this

![image](https://github.com/user-attachments/assets/1437434e-2552-4c10-a3ee-b1c0cc9450fd)

normal 3d printers use 3 axes (x, y, z). a 5-axis printer adds two more rotational axes. this lets it print more complex shapes with fewer supports and smoother surfaces.  

## bill of materials (wip)

i’m keeping a list of all the parts i'm using. it’s not final yet.  
[bom](https://1drv.ms/x/c/a3f42e945c9caa44/EbQFKpQWxlxJoD3NqtjWvSIBQ96Bu_KVVyi092GPrF79ng?e=d1bzi9)

| Component                         | Price (INR) | Quantity                                               | Link |
|-----------------------------------|-------------|--------------------------------------------------------|------|
| 2020 extrusion                    | 3000        | 8.5m                                                  | [Link](https://novo3d.in/aluminium-profiles-2020/?srsltid=AfmBOoqdCIagKlnxuTtaedS3pP4a6XTQNW1oaKr_tbyDSgIuxD1gO6ok) |
| linear rail (mgn12c)             | 2080        | 4.2m                                                  | asdasd |
| linear rail block (mgn12c)       | 5000        | 11                                                    | asdasd |
| nema17hs4401                     | 3700        | 5 (6 for extruder, I already have a spare nema17hs3401) | [Link](https://www.amazon.in/dp/B0DGF3VZYT?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| lead screw                       | 780         | 3x430                                                 | [Link](https://robodo.in/products/500mm-trapezoidal-lead-screw-8mm-thread-2mm-pitch-lead-screw-with-copper-nut?variant=6509949091883) |
| lead screw anti-backlash        | 261         | 3                                                     | [Link](https://www.flyrobo.in/t8-anti-backlash-spring-loaded-nut-for-8mm-threaded-rod-lead-screw-2*2mm) |
| 4010 fan                         | 200         | 2                                                     | [Link](https://robocraze.com/products/dc-12v-4cm-5010-double-ball-cooling-fan-durable-turbo-blower?variant=46397911433440) |
| e3d revo6                        | 1600        | 1                                                     | [Link](https://nl.aliexpress.com/item/1005009068669267.html) |
| dual gear drive extruder        | 575         | 1                                                     | [Link](https://www.amazon.in/dp/B08BNL96DX?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) |
| 16t idler pulley for GT2        | 360         | 6                                                     | [Link](https://www.flyrobo.in/16-tooth-3mm-bore-gt2-timing-idler-aluminum-pulley-for-6mm-belt) |
| 16t smooth idler pulley for GT2 | 120         | 2                                                     | [Link](https://robocraze.com/products/gt2-perlin-driven-aluminium-pulley-5mm-bore?currency=INR&variant=40193985020057) |
| nuts and bolts                  | 300         | many                                                  | [Link](https://onlyscrews.in/) |
| BL sensor                        | 4000        | 1                                                     | [Link](https://novo3d.in/bl-touch/) |
| BTT Octopus                      | 4100        | 1                                                     | [Link](https://biqu.equipment/products/bigtreetech-octopus-pro-v1-0-chip-f446?variant=40144816767074) |
| GT2 belt                         | 100         | 3m                                                    | [Link](https://robu.in/product/1m-gt2-width-6mm-black-open-timing-belt-for-3d-printer/) |
| endstops (already have)          | 0           | 2                                                     | - |
| wire                             | 99          | yes                                                   | [Link](https://www.amazon.in/dp/B0BVSM7N3L?ref=ppx_yo2ov_dt_b_fed_asin_title&th=1) |
| PSU 24V 14.6A 350W               | 2800        | 1                                                     | [Link](https://robu.in/product/lrs-350-24-mean-well-smps-24v-14-6a-350-4w-metal-power-supply/) |
| PTFE tube                        | 83          | 1m                                                    | [Link](https://robu.in/product/ptfe-2x4mm-teflon-tubing-for-3d-printers-1-75mm-filament-1m/) |
| heatbed knob set                 | 550         | 1                                                     | [Link](https://www.amazon.in/dp/B088KQJZGZ?ref=ppx_yo2ov_dt_b_fed_asin_title) |
| aluminium hotend bracket         | 200         | 1                                                     | [Link](https://novo3d.in/e3d-v6-fixed-block/?srsltid=AfmBOoqyDchvfV7eVUtRWugY3-ZiZzQdNxPYCzO2kWgDJ7uAW5NWGPU8KmU) |
| coupler 5x8mm                    | 52          | 3                                                     | [Link](https://robu.in/product/aluminium-flexible-coupling-coupler-helical-shaft-5mm-x-8mm/) |
| T-slot nuts for 2020            | 970         | 100                                                   | [Link](https://novo3d.in/sliding-t-nut/) |
| 300x300 heatbed                 | 1600        | 1                                                     | asdasdw124 |
| **TOTAL**                        | **32530**   |                                                        |      |


## build journal

im writing down ideas, issues, and updates as i go.  
[journal](https://github.com/Fastestkyo/5-axis-printer/blob/main/journal.md)

## how to guide

this is a tutorial for how to build this printer.
[how to](https://docs.google.com/presentation/d/14-imUmjOe8GsNLc_C2gs7DdIq2Uft8Xhfen-554Q0Uw/edit?usp=sharing)

## CAD
the 3d model of the entire printer.
i have cad files in the CAD directory, of the printer and the 3d printed parts.
[cad](https://a360.co/3HxWdIz)

# INFO
- the 5 axis printer includes 2 rotational axes. this lets it print with less overhangs.
## X & Y AXIS
-for this im going to be using the corexy belt xy system. 
![image](https://github.com/user-attachments/assets/606f7784-0c9a-44cc-a987-2eb4aae31f2f)

## Z AXIS
- the z axis will be fused with the ab axis, so there are 3 lead screws with 2 linear rails next to them. they will be connected to a 3d printed part which will have a place for a sphere object. 

## project status

this project is still in progress. i wil be updating the journal.md from time to time


