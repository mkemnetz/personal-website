---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Analysis of the aero-optical component of the jitter using the Stitching Method"
authors: [Matthew R. Kemnetz]
date: 2019-07-19
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-05-08T00:32:06-06:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "One of the major quantities of interest for airborne laser systems is the unsteady variation in pointing direction of the beam, or jitter. In airborne laser systems, the beam jitter is usually thought of as sourced from two components. The component of the jitter caused by mechanical vibration of the optical table, optical elements, etc. is called mechanical jitter. The component of jitter caused by flow structures on the order of the aperture size is called the aero-optical jitter. In typical experiments, information pertaining to the aero-optical component of the jitter is almost always corrupted by mechanical disturbances and is typically removed from the data.<br><br>

In this work an algorithm was developed that takes advantage of the advective nature of aberrations to compensate for the tip, tilt, and piston removal in experiment. The algorithm is able to recover the aero-optical component of the jitter and to provide time series of global tilt free of mechanical disturbances. This algorithm is called the stitching method. The stitching method was extensively modeled using a sine wave with added noise as a surrogate wavefront. Experiments were conducted in Notre Dame’s Tri-sonic Wind Tunnel (TWT) Facility. Optical wavefront measurements were conducted on a Mach 0.6/0.1 shear layer and Mach 0.2 boundary layer. In the Mach 0.6/0.1 shear layer experiment voice coil actuators were placed on the splitter plate to regularize the shear layer. Optical data for both forced and unforced shear layers were collected.<br><br>

The stitching method was used to recover the aero-optical component of the jitter for the experiments described. The predicted results for the RMS of the aero-optical jitter from the stitching method matched well with modeled results. Since the stitching method produces full time series of global tilt, energy spectra were also computed and presented. This information can be used by systems designers to benchmark fast steering mirrors for use in airborne directed energy systems. Finally, additional data collected by other researchers in flight aboard the Airborne Aero-Optics Laboratory (AAOL) were analyzed. Both the RMS of the global tilt and the global tilt energy spectra were computed. The results were found to agree well with the results from other shear layer flows."

# Summary. An optional shortened abstract.
summary: "One of the major quantities of interest for airborne laser systems is the unsteady variation in pointing direction of the beam, or jitter. In airborne laser systems, the beam jitter is usually thought of as sourced from two components. The component of the jitter caused by mechanical vibration of the optical table, optical elements, etc. is called mechanical jitter. The component ..."

tags: [Stitching Method, Jitter, Aero-Optics, Adaptive Optics, Wavefront Sensing, Directed Energy, Fluid Mechanics]
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf:
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
