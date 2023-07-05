# Occam

[Occam](https://www.occam3d.com/) is a bump map generator for 3D modelling.

In 3D modeling, a bump map is a technique used to simulate the appearance of surface details and texture on a 3D object without actually altering its geometry. It is a type of texture map that stores information about surface normals or height variations.

Typically, a bump map consists of grayscale values, where each pixel represents a height or normal displacement. The brighter areas of the map correspond to raised areas on the surface, while the darker areas represent recessed or indented regions. By applying the bump map to a 3D model, the renderer or game engine can calculate the lighting and shading as if the surface had actual geometry variations, creating the illusion of depth and surface irregularities.

The bump map is often used in conjunction with a 3D model's original low-polygon geometry to enhance its visual appearance and level of detail without adding unnecessary complexity to the mesh. This technique helps save computational resources and rendering time since the high-resolution details are simulated using the bump map instead of increasing the polygon count of the model.

Bump maps can be created using various software applications, such as texture painting tools or dedicated bump mapping tools. They are commonly employed in various areas of 3D graphics, including video games, computer-generated imagery (CGI), visual effects, and animation, to enhance the realism of objects and surfaces.

It's worth noting that bump mapping is a form of "simulated" geometry and doesn't actually alter the physical structure of the 3D model. Therefore, the perception of depth and surface details is dependent on the lighting and shading calculations performed during rendering, rather than actual changes in the model's geometry.

This repo only contains the build code. The source code is not available. The project uses react, javascript and chakra for the front end and runs on AWS Amplify. The domain is registered with [go-daddy](https://hk.godaddy.com/en) and AWS Route 53.

## Examples

Todo.
