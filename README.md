# SwiftDemo

Premiere Sphere
```
let sphereGeometry = SCNSphere(radius: 1.0)
let sphereNode = SCNNode(geometry: sphereGeometry)
scene.rootNode.addChildNode(sphereNode)
```

Deuxieme Sphere
```
let secondSphereGeometry = SCNSphere(radius: 0.5)
let secondSphereNode = SCNNode(geometry: secondSphereGeometry)
secondSphereNode.position = SCNVector3(x: 3.0, y: 0.0, z: 0.0)
scene.rootNode.addChildNode(secondSphereNode)
```
