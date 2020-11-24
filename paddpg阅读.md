1.网络：
```python
Actor: Actor(
  (layers): ModuleList(
    (0): Linear(in_features=59, out_features=1024, bias=True)
    (1): Linear(in_features=1024, out_features=512, bias=True)
    (2): Linear(in_features=512, out_features=256, bias=True)
    (3): Linear(in_features=256, out_features=128, bias=True)
  )
  (action_output_layer): Linear(in_features=128, **out_features=3**, bias=True)
  (action_parameters_output_layer): Linear(in_features=128, **out_features=5**, bias=True)
  (action_parameters_passthrough_layer): Linear(in_features=59, out_features=5, bias=True)
)
Critic: Critic(
  (layers): ModuleList(
    (0): Linear(in_features=67, out_features=1024, bias=True)
    (1): Linear(in_features=1024, out_features=512, bias=True)
    (2): Linear(in_features=512, out_features=256, bias=True)
    (3): Linear(in_features=256, out_features=128, bias=True)
  )
  (output_layer): Linear(in_features=128, out_features=1, bias=True)
)
```