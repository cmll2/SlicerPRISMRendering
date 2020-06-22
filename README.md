# SlicerPRISM

## Introduction and Acknowledgements
**Title**: SlicerPRISM
**Author(s)/Contributor(s)**: Simon Drouin, Professor at École de technologie supérieure (ÉTS), Montréal, Tiphaine RICHARD, Student Intern at ÉTS.
**License**: slicer4
**Acknowledgements**: This work is part of 

**Contact**: Tiphaine RICHARD, <email>tiphainejh@gmail.com</email>

## Module Description
This module provides interactive visualization of 3D image data.


## Use Cases

## Tutorials

## Panels and their use

Parameters : 
<table>
    <tr>
        <td>
            <ul> 
                <li><b>Data</b> : Contains the volume required for SlicerPRISM. </li>
                <ul>
                    <li><b>Image Volume</b> : Select the current volume to render. </li>
                </ul>
            </ul>
        </td>
        <td>
            <img src="/SlicerPRISM/Resources/Documentation/Data.png" alt="Data" style="float:right;" width ="300"	title="Data"/>
        </td>
    </tr>
    <tr>
        <td>
            <ul> 
                <li> <b>View Setup</b> : Contains the controls for rendering the volume as well as controls for the cropping box (ROI) of the volume. </li>
                <ul>
                    <li><b>Volume Rendering</b> : Enable/Disable rendering the volume.</li>
                    <li><b>Enable Cropping</b> : Enable/Disable cropping the volume.</li>
                    <li><b>Display ROI</b> : Enable/Disable displaying the ROI of the volume.</li>
                    <li><b>Enable Scaling</b> : Enable/Disable scaling the ROI of the volume.</li>
                    <li><b>Enable Rotation</b> : Enable/Disable rotating the ROI of the volume.</li>
                </ul>
            </ul>
        </td>
        <td>
            <img src="/SlicerPRISM/Resources/Documentation/ViewSetup.png" alt="ViewSetup" style="float:right;" width ="300"	title="ViewSetup"/>
        </td>
    </tr>
    <tr>
        <td>
            <ul> 
                <li><b>Custom Shader</b> : Controls of the shader.</li>
                <ul>
                    <li><b>Custom Shader</b> : Name of the shader to be applied during the rendering.</li>
                    <li><b>Reload</b> : Reload the current shader.</li>
                    <li><b>Open</b> : Open the current shader source code.</li>
                    <li><b>Duplicate</b> : Duplicate the current shader source code.</li>
                </ul>
            </ul>
        </td>
        <td>
            <img src="/SlicerPRISM/Resources/Documentation/CustomShader.png" alt="CustomShader" style="float:right;" width ="300"	title="CustomShader"/>
        </td>
    </tr>
    <tr>
        <td rowspan=3>
            <ul> 
                <li><b>Modify or Create Custom Shader</b> : Create or Modify a custom shader and add parameters.</li>
                <ul>
                    <li><b>Shader</b> : Name of the shader to modify or *Create new Custom Shader* to create a new one.</li>
                    <li><b>Class Name</b> : Name of the class that will be created.</li>
                    <li><b>Display Name</b> : Name of the shader that will be displayed in the UI.</li>
                    <li><b>Create</b> : Create the class.</li>
                    <li><b>Add Code</b> : Add a code that will replace a specific shader tag in the shader.</li>
                    <ul>
                        <li><b>Tag Type</b> : Type of the tag to be remplaced in the shader.</li>
                        <li><b>Shader Tag</b>: Tag to be remplaced in the shader.</li>
                        <li><b>Shader Code</b> : Code to replace the specified tag in the shader. Can be added directly in the </li>file by clicking *Open File*.
                        <li><b>Open File</b> : Open the class containing the shader.</li>
                        <li><b>Modify</b> : Apply the modifications the the class.</li>
                    </ul>
                    <li><b>Add Param</b> : Add specified parameters to the class that will be used in the shader.</li>
                    <ul>
                        <li><b>Type</b> : Type of the parameter.</li>
                        <li><b>Name</b> : Name of the parameter that will be used in the shader.</li>
                        <li><b>Display Name</b> : Name of the parameter that will be displayed in the UI.</li>
                        <li><b>Add Parameter</b> : Add the parameter in the class.</li>
                    </ul>
                </ul>
            </ul>
        </td>
        <td>
            <img src="/SlicerPRISM/Resources/Documentation/MCCustomShader.png" alt="MCCustomShader" style="float:right;" width ="300"	title="MCCustomShader"/>
        </td>
    </tr>
    <tr>
        <td>
            <img src="/SlicerPRISM/Resources/Documentation/MCCustomShaderCode.png" alt="MCCustomShaderCode" style="float:right;" width ="300"	title="MCCustomShaderCode"/>
        </td>
    </tr>
    <tr>
        <td>
            <img src="/SlicerPRISM/Resources/Documentation/MCCustomShaderParam.png" alt="MCCustomShaderParam" style="float:right;" width ="300"	title="MCCustomShaderParam"/>
        </td>
    </tr>

</table>

## Similar Modules

## References

## Information for Developers

### Limitations

### Key nodes and classes

### How Tos

