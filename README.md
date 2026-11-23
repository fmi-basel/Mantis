<img width="4616" height="873" alt="Asset 23@600x" src="https://github.com/user-attachments/assets/f4b872a4-5082-4c27-983b-805f2557d8e0" />

<br> Welcome to the `Mantis` landing page! `Mantis` is an ecosystem of modular tools for image processing and quantitative analysis of high-content, multiplexed, and volumetric microscopy data. The name is inspired by the mantis shrimp and its complex visual system, which detects light across multiple spectral channels 🦐🌈


<img width="4893" height="2245" alt="Asset 2@600x" src="https://github.com/user-attachments/assets/0fa294b0-90d4-4990-b046-5bbe91dbb54e" />

<br> `Mantis` functions are wrapped as [Fractal](https://fractal-analytics-platform.github.io/) tasks operating on the [OME-Zarr](https://ngff.openmicroscopy.org/) image format, enabling reproducible image-processing workflows. They can be combined and executed within a Fractal deployment alongside other tools from the Fractal ecosystem.

<br> An example `Mantis` workflow combining multiple tasks is shown below:

<br> 
<img width="4094" height="1890" alt="Asset 4@600x" src="https://github.com/user-attachments/assets/1eb2ba77-886f-422b-840c-b388d3040998" />

<br><br> The `Mantis` ecosystem consists of four complementary packages, organized by functionality:

<br> 
<table>
  <tr>
    <th></th>
    <th>Package</th>
    <th>Main functionality</th>
  </tr>
  <tr>
    <td>
      <img width="100" alt="Mantis-plex" src="https://github.com/user-attachments/assets/c38bc920-7893-4149-a2be-1279cb91c20a" />
    </td>
    <td>
      <a href="https://github.com/fmi-basel/Mantis-plex">Mantis-plex</a>
    </td>
    <td>
      Registration of 3D images across multiplexed imaging rounds.
    </td>
  </tr>
  <tr>
    <td>
      <img width="100" alt="Mantis-surf" src="https://github.com/user-attachments/assets/f1240c60-b9de-41c3-bc7a-ee3fd90860fe" />
    </td>
    <td>
      <a href="https://github.com/fmi-basel/Mantis-surf">Mantis-surf</a>
    </td>
    <td>
      3D surface segmentation of tissues.
    </td>
  </tr>
  <tr>
    <td>
      <img width="100" alt="Mantis-seg" src="https://github.com/user-attachments/assets/34c716cf-b2b7-4235-bfb1-17109e42f705" />
    </td>
    <td>
      <a href="https://github.com/fmi-basel/Mantis-seg">Mantis-seg</a>
    </td>
    <td>
      Segmentation of cells and nuclei in 3D tissues.
    </td>
  </tr>
  <tr>
    <td>
      <img width="100" alt="Mantis-quant" src="https://github.com/user-attachments/assets/2ff40414-e776-4b24-8ad6-cc7a38888e93" />
    </td>
    <td>
      <a href="https://github.com/fmi-basel/Mantis-quant">Mantis-quant</a>
    </td>
    <td>
      Quantification of segmentation features, marker intensities, spatial organization and mesh annotation.
    </td>
  </tr>
</table>
