## Assessment of algorithms for mitosis detection in breast cancer histopathology images（2014）

### AMIDA2013
Assessment of Mitosis Detection Algorithms 2013, one thousand annotated mitotic figures by multiple observers

the proliferation of cells :
```
resting phase(G0)
first gap phase(G1)
synthesis phase(S)
second gap phase(G2)
mitosis phase(M)
```

An automatic mitosis detection method with good performance could alleviate both the subjectivity and the tediousness
of mannual mitosis counting.

### Preprocess
1.
```
L from LAB color space
V and L from LUV color space
bule ratio image(ratio of the blue color channel and the sum of the other two channels in the RGB)
```

For each HPF, a set of candidate regions was defines by thresholding the bule ratio image.

Staining normalization by non-linear color mapping was performed in order to neutralize the inherent variation in the color of the staining

### Feature extraction and classification
The threshold value for obtaining the binary map was selected by preforming receiver operating characteristic(ROC) vurve analysis

contexture features(first order statistics over a set of textural features)
