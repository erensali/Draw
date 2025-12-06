# Draw
Overview: "Draw" is a lightweight, feature-rich vector graphics editor built using the .NET Framework and Windows Forms. Designed to demonstrate the principles of computer graphics, this application allows users to create, manipulate, and transform geometric primitives in a 2D space. Unlike raster paint programs, "Draw" treats every shape as an independent object, allowing for non-destructive editing and precise control.

Key Features:

Geometric Primitives: Create perfect Rectangles, Ellipses, Lines, and Points.

Object Manipulation: Select specific shapes, drag to move them, and resize them dynamically.

Transformation Engine: Apply geometric transformations including Scaling, Translation, and Rotation.

Style Customization: Full control over Fill Colors (Interior) and Stroke Colors (Border), as well as adjustable opacity and border thickness.

Group Operations: (If applicable) Group multiple objects to manipulate them as a single unit.

Persistency: Save your work and load it later to continue editing.

Technical Stack:

Language: C#

Framework: .NET / Windows Forms

Rendering: GDI+ (System.Drawing)

Architecture: MVC-inspired separation of Model (Shapes), View (Form), and Controller (Processors).
