# ManageArtworks-SnapTo

## Installation and setup
1. `git clone <repo-link>`
2. `code <directory-path>`
3. `yarn install`
4. `yarn start`
5. A chrome tab in `localhost:3000` will open

## Usage
1. Choose your vector pdf
2. Click on the measurement tool
3. Check the `enable snapping for measurement tools`
4. Choose the line measurement tool
5. Hover over the corners of the required rectangles
6. Drag the line measurement tool to the opposite corner
7. Approve or remove the rectangle
8. Convert it to a `gltf` file using the `Convert` button

## Implementation
1. Enabled the measurement tools and snapping using `fullAPI`
2. Set eventListeners to the DOM object of the vector pdf
3. Converted the image to dataURLs
4. Used the old logic to convert to `gltf`

## Problems
1. There is a vertical offset in the selected rectangle
