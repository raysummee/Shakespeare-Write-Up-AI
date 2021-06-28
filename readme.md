
# Shakespeare Write-Up AI

## NLP AI to generate paragraph that shakespeare would have written from a single word

<br/>

> ### Requirements:
> - Tensorflow
> - Pandas
> - Numpy
> - matplotlib

<br/>

## Brief: 
The program is using Recurrent neural networks (RNN).

> ## Model: "sequential"
> ---
> | Layer (type)         | Output Shape     | Param # |
> | -------------------- | ---------------- | ------- |
> | embedding (Embedding)| (128, None, 64)  | 5376    |
> | gru (GRU)            | (128, None, 1026 | 3361176 |
> | dense (Dense)        | (128, None, 84)  | 86268   |

<br/>

## Example:

```python
print(generate_text(model, "JULIET", gen_size=1000))
```
> ## Output: 
> JULIETHIUS. She comes from his behalf take up resolve.
  OLIVIA. I will, my sword. Know, my lord,
    I cannot ever since my painful man,
    And there to save with likewise which
    Wept bargains, and how his grasping hand in him,
    Will put it up to argusy good creation; but
    My little bed-world's ntstance keep
    The reading and indusicatique to us! Mistress May,  
    Let me be rough to fear content I would,
    And gave them not to sleep. My house to brave,
    Read not the soul upon your Grace becomes yellven
    For Thesess, miracles!
  GLOUCESTER. I get so oft that horse the one might commend.
  SEBASTIAN. I had. Then the Moon'st article I have destroy'd,
    Balifous any in my mountaines better,
    Even to myself wants, and raise departure,
    And the weak ragged thanks I do excuse
    You would have tongue?
  DEMETRIUS. Shame got we be lack'd
    even hollowed thy face.
  COSTARD. Grandam, what needs there.
  THURIO. Then thou art daggers! Hence!         Descends.
>
> Pob. 

