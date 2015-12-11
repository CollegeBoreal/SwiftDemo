# SwiftDemo

La Terre
```
let sphereGeometry = SCNSphere(radius: 1.0)
let sphereNode = SCNNode(geometry: sphereGeometry)
scene.rootNode.addChildNode(sphereNode)
```

La Lune
```
let secondSphereGeometry = SCNSphere(radius: 0.5)
let secondSphereNode = SCNNode(geometry: secondSphereGeometry)
secondSphereNode.position = SCNVector3(x: 3.0, y: 0.0, z: 0.0)
scene.rootNode.addChildNode(secondSphereNode)
```

Mars
```
sphereGeometry.firstMaterial?.diffuse.contents = UIColor.redColor()
```

Inspire de:
https://www.weheartswift.com/introduction-scenekit-part-1/
