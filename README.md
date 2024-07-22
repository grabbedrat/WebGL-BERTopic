# WebGL-BERTopic

## Overview
WebGL-BERTopic is an innovative implementation of the BERTopic algorithm using WebGL for GPU-accelerated processing in web browsers. This project aims to bring the power of advanced topic modeling to client-side applications, enabling privacy-preserving, accessible, and interactive topic analysis directly in the browser.

## Features
- Browser-based topic modeling using BERT embeddings
- GPU acceleration via WebGL for improved performance
- Interactive visualizations of topic clusters
- Privacy-preserving: all processing done client-side
- Responsive design for various devices and screen sizes

## Installation
```bash
git clone https://github.com/yourusername/webgl-bertopic.git
cd webgl-bertopic
npm install
```

## Usage
```javascript
import { WebGLBERTopic } from 'webgl-bertopic';

const documents = ["Your list", "of documents", "to analyze"];
const model = new WebGLBERTopic();
const topics = await model.fit_transform(documents);
```

## Requirements
- Modern web browser with WebGL 2.0 support
- Node.js and npm for development

## Development
```bash
npm run dev
```

## Building
```bash
npm run build
```

## Testing
```bash
npm test
```

## Contributing
We welcome contributions! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) for details on how to submit pull requests, report issues, or request features.

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments
- Original BERTopic implementation by Maarten Grootendorst
- BERT developers at Google Research

## Citation
If you use WebGL-BERTopic in your research, please cite:

```bibtex
@software{webgl_bertopic,
  author = {Your Name},
  title = {WebGL-BERTopic: GPU-Accelerated Topic Modeling in the Browser},
  year = {2024},
  url = {https://github.com/yourusername/webgl-bertopic}
}
```
