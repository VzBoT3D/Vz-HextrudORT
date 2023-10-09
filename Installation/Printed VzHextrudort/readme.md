# Printed Vz-HextrudORT

## Assembly

Please see the [BOM](#bom) for the hardware, tools, materials and printed parts you will need.

| Exploded diagram                                                  | Printed parts |
| ----------------------------------------------------------------- | ------------- |
| ![Vz-HextrudORT exploded assembly](./VZHextrudort%20Assembly.png) |               |

## Mounting

All versions of the Vz-HextrudORT have the same bolting pattern. They can be mounted from the bottom of the extruder using M3 screws. The spacing between the mounting holes is 19mm, exactly the same as the BondTech LGX Lite extruder.

You will also need a piece of a PTFE tube between the extruder and the hotend. The lenght vary depending on the extruder and the mounting option.

## BOM

### Hardware

| Item                       | Quantity | Comment                      | Image                         | Links                                       |
| -------------------------- | -------- | ---------------------------- | ----------------------------- | ------------------------------------------- |
| Push-fit pneumatic coupler | 1        | Optional, for reverse bowden | ![Push-fit pneumatic coupler] | <https://s.click.aliexpress.com/e/_AoAejk>  |
| LDO NEMA14 17-20mm         | 1        |                              | ![LDO NEMA17 pancake stepper] | <https://s.click.aliexpress.com/e/_Dcwpt5T> |
| BMG Gear set               | 1        |                              | ![Direct drive basic kit]     | <https://s.click.aliexpress.com/e/_DCNS1qz> |
| M3 Nut                     | 2        |                              |                               | <https://s.click.aliexpress.com/e/_AFJSUp>  |
| M3x6 SHCS                  | 2        |                              |                               | <https://s.click.aliexpress.com/e/_9RMap3>  |
| M3x25 SHCS                 | 2        |                              |                               | <https://s.click.aliexpress.com/e/_9RMap3>  |
| M3x20 SHCS                 | 1        |                              |                               | <https://s.click.aliexpress.com/e/_9RMap3>  |
| M3x16 SHCS                 | 1        |                              |                               | <https://s.click.aliexpress.com/e/_9RMap3>  |

### Printed parts

Find all printed parts on the [Vz-HextrudORT](/STLs%20and%20BOM/STLs/Printed%20versions) GitHub page.

| Item                   | Quantity | Comment                      | Image | Links |
| ---------------------- | -------- | ---------------------------- | ----- | ----- |
| Reverse bowden adapter | 1        | Optional, for reverse bowden |       |       |

| Item                                   | Comment |
| -------------------------------------- | ------- |
| [Back plate (HIGH motor)]              |         |
| [Back plate (LOW motor)]               |         |
| [Front cover (HIGH motor)]             |         |
| [Front cover]                          |         |
| [Main body (LOW motor, helical gears)] |         |
| [Main body]                            |         |
| [Main body (RIDGA gears)]              |         |
| [Tensioner arm (helical gears)]        |         |
| [Tensioner arm (straight gears)]       |         |

[Back plate (HIGH motor)]: /STLs%20and%20BOM/STLs/Printed%20versions/Back%20plate%20High%20motor%20mount.stl
[Back plate (LOW motor)]: /STLs%20and%20BOM/STLs/Printed%20versions/Back%20plate%20Low%20motor%20mount.stl
[Front cover (HIGH motor)]: /STLs%20and%20BOM/STLs/Printed%20versions/front%20cover%20high%20motor.stl
[Front cover]: /STLs%20and%20BOM/STLs/Printed%20versions/front%20cover.stl
[Main body (LOW motor, helical gears)]: /STLs%20and%20BOM/STLs/Printed%20versions/main%20body%20low%20motor%20helical%20gears.stl
[Main body]: /STLs%20and%20BOM/STLs/Printed%20versions/main%20body.stl
[Main body (RIDGA gears)]: /STLs%20and%20BOM/STLs/Printed%20versions/Main-Body-RIDGA.stl
[Tensioner arm (helical gears)]: /STLs%20and%20BOM/STLs/Printed%20versions/tension%20arm%20helical%20gears.stl
[Tensioner arm (straight gears)]: /STLs%20and%20BOM/STLs/Printed%20versions/tension%20arm.stl

Parts specific to the ERFC version of the Vz-HextrudORT:

| Item                           | Comment  |
| ------------------------------ | -------- |
| [Back plate (LOW motor, ERFC)] | For ERCF |
| [Main body (ERFC)]             | For ERCF |

[Back plate (LOW motor, ERFC)]: /STLs%20and%20BOM/STLs/Printed%20versions/ERCF%20version/Back%20plate%20Low%20motor%20mount-ERCF.stl
[Main body (ERFC)]: /STLs%20and%20BOM/STLs/Printed%20versions/ERCF%20version/main%20body-ERCF.stl

### Tools

- Hex wrench, 2.5mm (for M3 SHCS)
- Spanner, 5.5mm (for M3 nuts)
- Soldering iron (for threaded inserts)

[Push-fit pneumatic coupler]: https://user-images.githubusercontent.com/37383368/146020643-7de56373-1956-430e-af35-fa52e62a8844.PNG
[LDO NEMA17 pancake stepper]: https://github.com/VzBoT3D/Vz-HextrudORT/assets/16231288/8cdf1362-4152-4834-b42d-a79e6cd66989
[Direct drive basic kit]: https://github.com/VzBoT3D/Vz-HextrudORT/assets/16231288/12b2ac00-62e9-4d91-b8a6-19044f50e67a
