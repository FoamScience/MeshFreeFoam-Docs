---
api_tags:
  - method
contributors:
  - elwardi
hyde:
  brief: __INLINED__
  defined_in_file: https://github.com/FoamScience/MeshFreeFoam/blob/master/src/meshfree/shapes/basicShape/basicShape.H
  inline:
    brief: _multiple descriptions_
    owner: elwardi
  is_ctor: true
  overloads:
    basicShape<positionType>(basicShape<positionType> &&):
      annotation:
        - deleted
      arguments:
        - description: __OPTIONAL__
          name: other
          type: basicShape<positionType> &&
      description: __INLINED__
      inline:
        description:
          - Move construct
      key: basicShape<positionType>(basicShape<positionType> &&)
      signature_with_names: basicShape<positionType>(basicShape<positionType> && other)
    basicShape<positionType>(const basicShape<positionType> &):
      annotation:
        - deleted
      arguments:
        - description: __OPTIONAL__
          name: other
          type: const basicShape<positionType> &
      description: __INLINED__
      inline:
        description:
          - Delete default copy construct
      key: basicShape<positionType>(const basicShape<positionType> &)
      signature_with_names: basicShape<positionType>(const basicShape<positionType>
        & other)
    explicit basicShape<positionType>(const Foam::dictionary &):
      arguments:
        - description: __OPTIONAL__
          name: dict
          type: const Foam::dictionary &
      description: __INLINED__
      inline:
        description:
          - Construct from dictionary
      key: explicit basicShape<positionType>(const Foam::dictionary &)
      signature_with_names: explicit basicShape<positionType>(const Foam::dictionary
        & dict)
  owner: __INLINED__
  tags:
    - method
layout: method
title: basicShape<positionType>
---
