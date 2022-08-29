
# `Spline 3d`

`Spline - 3D Design Tutorial`

<p align="center">
 <img width="550px" src="https://images.ctfassets.net/ooa29xqb8tix/3o9JjDLNNqNyctDjtHUg2T/50b3c6a6abb2c3a1a1969803d87349ed/Create_3D_site_with_Spline_and_React_image_1.jpg" align="center" alt="GitHub Readme Stats" />
 <h2 align="center">Spline 3d Design For Web</h2>
</p>

Login to [Spline](https://app.spline.design/signin)


---

## Quick Links

- [Spline](#spline)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [Spline Object Parameters](#spline-object-parameters)
- [Spline Animation Parameters](#spline-animation-parameters)
- [Export File Format](#export-file-format)



---

## Spline

Designing in 3D has never been easier. Create 3D scenes, edit materials, and model 3D objects. Control the outcome of your design work.

---

## Keyboard Shortcuts

There are few keyboard shortcuts of Spline. They are:


| Command            | Keys                                  |   |  |
|:-------------------|:--------------------------------------|---|--|
| Orbit              | `Option` + `Mouse Click`              |   |  |
| Sizing             | `Shift` + `Drag`                      |   |  |
| Sizing Ratio       | `Shift` + `Option` + `Drag`           |   |  |
| Pan                | `Space` + `Drag`                      |   |  |
| Zoom               | `Mouse Scroll`                        |   |  |
| Zoom +/-           | `Cmd` + `+/-`                         |   |  |
| Copy               | `Cmd` + `D`                           |   |  |
| Select Multiple    | `Shift` + `Mouse Click`               | * |  |
| Rectangle          | `R`                                   | * |  |
| Ellipse            | `O`                                   | * |  |
| Triangle           | `K`                                   | * |  |
| Pentagon           | `J`                                   | * |  |
| Reset Camera       | `Mouse Right Click` > `View`          | * |  |
| Copy Material      | `Mouse Right Click` > `Copy Material` | * |  |


---

## Spline Object Parameters

Here are few object parameters to speed up the Spline workforce.

`Rectangle` Parameters

```
Rectangle (Frontend UI)
├── Shape
|   └── Size: 1280 * 844
└── Material
    ├── Image: Upload Image
    └── Glass
        └── Blur: 25
```

`Pentagon` Parameters

```
Pentagon (Avatar)
├── Shape
|   ├── Side:       6
|   ├── Corner:     10
|   └── Extrusion:  10
├── Material
|    ├── Image: Upload Image
|    └── 
└── Material (2nd)
    └── Depth
        ├── Ramp(range):   Opacity: 0
        ├── Color:  Dark
        ├── Type:   Linear
        ├── Direction:   Z 1
        ├── Near:   9.9
        └── Far:    10
```

`Rectangle` Parameters

```
Rectangle (Banner)
├── Shape (Not Copied, Put Manually)
|   ├── Size:       667 * 180
|   ├── Position:   Z 10
|   ├── Corner:     20
|   └── Extrusion:  10
└── Material (Copied)
```

`Sphere` Parameters

```
Sphere (Blob)
├── Shape
|   └── Size: 1000 * 1000 * 1000
├── Smooth
|   └── Level 4
├── Material
|   └── Displace  295    690
|       └── Simplex: 1.7  1
└── Material (2nd)
    ├── Lighting: None
    └── Depth
         ├── Ramp(range):
         ├── Color:  Bluish
         ├── Near:   360
         └── Far:    650
```


---

## Spline Animation Parameters

Here are few animation parameters to speed up the Spline workforce.

- `Basic State` indicates `Start` Position
- `State` indicates `End` Position
- `Event` indicates animation `Time`

Events act according to a particular State which is mentioned inside `State` segment inside Event. 

`State` Parameters

```
State
├── Basic State
|   └── Z-index: 10
├── State
|   └── Z-index: 80
├── Event
|   ├── Type:     Start
|   ├── State:    State
|   ├── Duration: 5s
|   └── Delay:    0.6
├── State 2
|   └── Material
|       ├── Color:   Opacity: 50
|       └── Depth
└── Event
    ├── Type:       Mouse Hover
    ├── State:      State 2
    └── Transition: Spring
```

---

## Export File Format

- Image
- Video
- GLTF
- URL


---

## Contributing

1. Fork it
2. Create your feature branch with specs (`git checkout -b my-cute-feature`).
3. Commit your changes (`git commit -m 'Added my cute feature'`).
4. Push to the branch (`git push origin my-cute-feature`).
5. Create your new pull request.

---

## Contributors

<table>
  <tr>
    <td align="center"><a href="https://jayedrashid.com/"><img src="https://avatars.githubusercontent.com/u/68325519?s=400&u=c3380d6ce56295f87d4f877de9ca04b7adf28d55&v=4" width="100px;" style="border-radius:50%; border:2px solid white;" alt=""/><br /><sub><b>Jayed Rashid</b></sub></a><br />   
  </tr>
</table>

---

## Let's Connect

Feel free to Contact me on [Twitter](https://mobile.twitter.com/jayedrashid), send an email to jayed@jayedrashid.com

<img height="20" src="https://www.bollywoodmdb.com/images/uparrow.gif"> [back to top](#quick-links)<br>



