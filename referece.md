## get parent
`parent = ctrl.getTransformParent()` - returns parent node

## find character element
`guidesskeleton = character.findCharacterElement('Guides.skel')`

## subnet set param & set tags
`mainsinenode = graph.addSubnet(contents=bodyMove, subnetname='mainMove')
mainsinenode.setParms({'frequency': frequency/4.0, 'amplitude': amplitude, 'body_ramp': body_ramp})
mainsinenode.setTags(['main_mover'])`
