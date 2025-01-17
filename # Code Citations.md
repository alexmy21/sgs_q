# Code Citations

## License: MIT
https://github.com/hpssjellis/my-examples-for-quantum-computing/tree/5235c682b0d2de2eaab8d52b84e295c9f4abf4e5/rocksetta/old/single-qbit01.py

```
, weights):
    qml.templates.AngleEmbedding(inputs, wires=range(n_qubits))
    qml.templates.StronglyEntanglingLayers(weights, wires=range(n_qubits))
    return [qml.expval(qml.PauliZ(i)) for i in range(n_qubits)]
```

