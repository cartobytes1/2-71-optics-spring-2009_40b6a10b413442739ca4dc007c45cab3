---
course_id: 2-71-optics-spring-2009
is_media_gallery: true
layout: course_section
menu:
  leftnav:
    identifier: 764fabe6d2d5ebc4839b60422b2be364
    name: Projects
    weight: 60
title: Projects
type: course
uid: 764fabe6d2d5ebc4839b60422b2be364

---

The purpose of the class projects is to familiarize you with topical Optics research and the research process in the Optics discipline; namely, how one goes from the basics that we learn in class to the open-ended problems where original contributions are possible. Within the scope of a class project we cannot of course expect to achieve the degree of originality that characterizes the forefront, but we can have a taste of some research components, e.g.

1.  selecting and criticizing the existing literature on a topic of interest,
2.  performing basic analytical and simple numerical calculations of feasibility in a design project, or
3.  performing the steps that are necessary to comprehend a new topic and explain to colleagues in a research team.

Depending on the topic you choose, you will experience primarily one of these three flavors or in some cases combinations. Original research is _not_ required or expected of these projects; however, in exceptional cases if your progress exceeds a certain threshold to be determined by the instructors, we will consider submission for publication in a peer-review journal or conference or filing a patent.

Below is a list of suggested projects. Alternatively, you are free to assemble a team and propose your own project(s) on a topic of your own choice. Several examples of student project [reports and presentations](#examples) are also listed at the end of the page.

1\. Geometrical Optics
----------------------

### 1.1 Design a Cooke Triplet

A Cooke triplet consists, as the name suggests, of three stacked lenses of different glasses. With proper use of the available seven degrees of freedom (four surfaces: front, back, and the two interior surfaces shared by the stacked elements; and the three indices of refraction) one can meet a focal length specification and also cancel three of the Seidel aberrations: spherical, coma, and astigmatism. In this project, you will use Zemax, an optical design software suite, to design a Cooke triplet and evaluate its performance.

[Student Project Video]({{< baseurl >}}/sections/projects/design-of-a-cooke-triplet)

### 1.2 Optical Cloaking

Consider an object that scatters light from an illuminating source and is, therefore, visible to an optical imaging system. If we enclose this object with an appropriate GRadient INdex (GRIN) distribution, we can in principle divert the light rays from the source so that the rays bypass the object before continuing towards the imaging system. This means that, as far as the imaging system is concerned, and while geometrical optics remains valid, there is no evidence of the object (or the GRIN) in the incoming field: we have "cloaked" the object, in other words we've made it invisible! In this project we'll use the Hamiltonian Optics formulation to study ray propagation in optical cloaks, and consider the following question: can a cloak be broken, i.e. can the wave nature of the optical field be used to reveal the hidden object?

2\. Digital Holography
----------------------

This term refers to an optical imaging technique that, like traditional holography, captures the complex amplitude of an optical eld (whereas non-holographic imaging techniques capture only the intensity.) As in traditional holography, the interference between the eld of interest and a reference field is formed and measured. Unlike traditional holography, however, its digital counterpart does not require the exposure of an interference patterns onto holographic film and the associated inconveniences; namely, chemical processing and optical reconstruction. Instead, in digital holography the interference pattern is exposed on a digital camera, e.g. CCD or CMOS and stored in computer memory. Field reconstruction can thus be done computationally.

### 2.1 Holographic Particle Image Velocimetry

Since the reconstruction is done digitally, "digital focusing" is an appealing capability. If the field originates in a relatively sparse three-dimensional volume, then by scanning the digital reconstruction kernel, we can bring different cross-sections of the volume to focus. The cross-sections are often referred to as "optical slices" and the procedure "optical slicing." A good example of a 3D field is that generated by a population of particles, such as glass spheres, that are coherently illuminated. If these particles are carried by a flow, then successive frames of digital holographic reconstructions are snapshots of the flow structure. This approach is known as "holographic particle image velocimetry" (HPIV). The project goal is to review the latest literature on HPIV, simulate test cases, and critique different approaches to the estimation of particle positions and velocities (the latter is non-trivial, as some thought will quickly convince you.)

[Student Project Video]({{< baseurl >}}/sections/projects/holographic-particle-image-velocimetry)

### 2.2 Holographic Tomography

If the volume of interest is relatively dense, the digital reconstruction becomes ill de-fined. Optical slicing can still be obtained, however, by rotating the sample and capturing interferograms at each angle. These are referred to as "projections." Subsequently, a mathematical procedure called Radon transform is applied to the projections in order to reconstruct the volume's interior. (The Radon transform mathematics is identical to the reconstruction procedure in Magnetic Resonance Imaging, though the physics of image formation are of course radically different.) The purpose of the project is to review the literature in this topic and perform some simple calculations, e.g. evaluate the number of projections required to capture an acceptable quality image as function of the optical density of the volume of interest.

[Student Project Video]({{< baseurl >}}/sections/projects/holographic-tomography)

### 2.3 Intensity Transport

This is really a competing method to digital holography. It originates with the observation that two measurements of the intensity at different planes perpendicular to the direction of propagation suffice to establish the phase and therefore measure the complex amplitude of the field. A neat derivation results in a differential equation relating the phase to the intensity gradient, and is known as "intensity transport equation." The goal of the project is to study the structure of the intensity transport equation, apply it to some test cases, and critique its sensitivity to sampling and noise. Ultimately, the goal is to compare intensity transport to digital holography as two alternate methods of establishing phase; but that could go well beyond the scope of a class project!

### 2.4 Wigner Transform and Integral Imaging

The Wigner transform is a tool that allows us to represent a signal in both the space and spatial frequency domains by using a form of localization: just as in a music piece you typically hear only a few frequencies at any given moment (whereas the Fourier transform of the entire piece would be much richer in spatial frequency content!) in optical signals the local frequency content may be more informative about the nature of the signal than the traditional Fourier representation. The Wigner transform is intimately associated with a very old imaging technique known as "integral imaging," where the image is formed by an array of pinholes: each pinhole captures rays propagating at a limited set of angles (and, therefore, spatial frequencies) from each object point and, in a sense, performs a Wigner transform on the object. (In modern systems the pinhole array is replaced with a lenslet array for better light capturing efficiency.) The goal of this project is to review the properties of integral imaging from the literature and evaluate (again, based on the literature or some simple numerical computations of limited scope) its applicability to imaging through obscuring media, such as foliage.

[Student Project Video]({{< baseurl >}}/sections/projects/wigner-distribution-function-and-integral-imaging)

3\. Subwavelength Optics
------------------------

As we discussed briefly in class, scalar wave optics fails when light propagates through features of size comparable to or smaller than the wavelength. A rigorous solution to Maxwell’s equations, taking into full account the vectorial nature of the electromagnetic field, is then required. Optical elements with strong subwavelength modulation referred to as "photonic crystals" have been of particular interest in the literature recently. These are dielectrics with periodic subwavelength patterns of high index contrast (e.g., air holes etched in silicon, which has index of refraction ≈ 3.4 in the near infrared.) it turns out that many photonic crystal geometries are completely opaque to light within a certain wavelength range referred to as the "bandgap." However, if a "defect" exists within the crystal, such as a cavity or a waveguide, then light is allowed to exist in a localized state within the defect. This concept has led to many interesting proposals for application to diverse fields, from highly compact integrated optical circuits for optical communications to high sensitivity single molecule spectroscopy.

### 3.1 Light Propagation in Sub-wavelength Modulated Media

One of the most effective tools for the numerical solution of Maxwell’s equations is the Finite Difference Time Domain method (FDTD). It applies the finite difference principle to four dimensions (three spatial plus time) and does some clever interpolations of the field derivatives to improve accuracy and speed. In this project, we will provide you with FDTD code developed by Prof. Steven Johnson (MIT Mathematics Department) and guide you how to use the code to simulate light propagation through a subwavelength grating. You will see that interesting things happen to the polarization in this case, and these become even more interesting if the grating is slightly chirped (i.e. with locally variable period.)

[Student Project Video]({{< baseurl >}}/sections/projects/light-propagation-in-sub-wavelength-modulated-media)

### 3.2 Light Propagation in Photonic Crystals

Light propagation in photonic crystals may be analyzed either with FDTD (see above) or with a method borrowed from solid state physics: since the photonic crystal geometry is periodic, the optical field must also be periodic with the same period or a harmonic. These periodic fields are referred to as "modes," and they can be computed as eigenfunctions of a special operator determined by the geometry; that is, we can predict the optical field in a photonic crystal without explicitly solving Maxwell's equations. In this project we will give you a photonic crystal structure of interest, help you use one of those mode solvers to calculate the field and then interpret the results of your calculation.

### 3.3 Accuracy Requirements in the Mechanical Assembly of Photonic Crystals

From a practical view point, photonic crystals are difficult to fabricate because they are three-dimensional structures with features smaller than the optical wavelength; for example, a photonic crystal intended to operate in visible wavelengths would have features smaller than 150nm. In this project, we will ask you to compare two published papers from the literature: one theoretical, estimating the sensitivity of photonic crystal properties (such as bandgap extent and localization) to misalignment between layers in the 3D structure; and one experimental which actually realized one of these layered structures. We will ask you to critique whether the experimental approach was compatible with the theoretical requirements on accuracy and consider alternative approaches to mechanical assembly.

[Student Project Video]({{< baseurl >}}/sections/projects/accuracy-requirements-in-the-mechanical-assessment-of-photonic-crystals)

{{< anchor "examples" >}}{{< /anchor >}}Student Work
----------------------------------------------------

All student presentations and reports are presented with permission of the authors.{{< video-gallery-item href="/sections/projects/design-of-a-cooke-triplet" section="Projects" title="Design of a Cooke Triplet" description="Project Topic : Design of a Cooke Triplet Speakers : Wonjoon Choi, Ryan Cooper, Qunya Ong, Matthew Smith" thumbnail="https://img.youtube.com/vi/vRhpH8siTNk/default.jpg" >}} {{< video-gallery-item href="/sections/projects/holographic-particle-image-velocimetry" section="Projects" title="Holographic Particle Image Velocimetry" description="Project Topic : Holographic Particle Image Velocimetry Speakers : Michael Barry, Alisha Schor, Anna Shih" thumbnail="https://img.youtube.com/vi/lazME0LEUzA/default.jpg" >}} {{< video-gallery-item href="/sections/projects/holographic-tomography" section="Projects" title="Holographic Tomography" description="Project Topic : Holographic Tomography Speakers : Aditya Bhakta, Danny Codd" thumbnail="https://img.youtube.com/vi/RizM3cD3XSA/default.jpg" >}} {{< video-gallery-item href="/sections/projects/wigner-distribution-function-and-integral-imaging" section="Projects" title="Wigner Distribution Function and Integral Imaging" description="Project Topic : Wigner Distribution Function and Integral Imaging Speakers : Michael McCanna, Shalin Mehta, Lei Tian, Michelle Lydia Kam Ye-Sien" thumbnail="https://img.youtube.com/vi/dWK25XcqFL4/default.jpg" >}} {{< video-gallery-item href="/sections/projects/light-propagation-in-sub-wavelength-modulated-media" section="Projects" title="Light Propagation in Sub-wavelength Modulated Media" description="Project Topic : Light Propagation in Sub-wavelength Modulated Media Speakers : Naveen Kumar Balla, Kalpesh Mehta, Chong Shau Poh" thumbnail="https://img.youtube.com/vi/_8TPfNfgH0I/default.jpg" >}} {{< video-gallery-item href="/sections/projects/accuracy-requirements-in-the-mechanical-assessment-of-photonic-crystals" section="Projects" title="Accuracy Requirements in the Mechanical Assessment of Photonic Crystals" description="Project Topic : Accuracy Requirements in the Mechanical Assessment of Photonic Crystals Speakers : Martin Deterre, Corey Fucetola, Sebastien Uzel" thumbnail="https://img.youtube.com/vi/WCw7gzz5RZY/default.jpg" >}}