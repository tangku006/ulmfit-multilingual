
# Label Smoothing
## Epochs 4
```
python -m ulmfit eval_noise_resistance --lang=es --size=10 --prefix-name="sl-e4" --model="sp15k/qrnn_nl4.m"  --num-cls-epochs=4 --label-smoothing-eps=0.1
python -m ulmfit eval_noise_resistance --lang=es --size=10 --prefix-name="sl-e4" --model="sp15k/qrnn_nl4.m"  --num-cls-epochs=4 --label-smoothing-eps=0.1
Noise:  0
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e40.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
/home/pczapla/anaconda3/envs/fastaiv1/lib/python3.7/site-packages/torch/utils/cpp_extension.py:152: UserWarning:

                               !! WARNING !!

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Your compiler (c++) may be ABI-incompatible with PyTorch!
Please use a compiler that is ABI-compatible with GCC 4.9 and above.
See https://gcc.gnu.org/onlinedocs/libstdc++/manual/abi.html.

See https://gist.github.com/goldsborough/d466f43e8ffc948ff92de7486c5216d6
for instructions on how to install GCC 4.9 or higher.
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

                              !! WARNING !!

  warnings.warn(ABI_INCOMPATIBILITY_WARNING.format(compiler))
Loss and accuracy using (cls_best): [0.2204297, tensor(0.9553)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e40.m',
              0.9552500247955322)])
Noise:  5
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e45.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [4.971248, tensor(0.8798)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e45.m',
              0.8797500133514404)])
Noise:  10
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e410.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [0.5768092, tensor(0.9420)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e410.m',
              0.9419999718666077)])
Noise:  15
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e415.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [1.2631954, tensor(0.9197)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e415.m',
              0.9197499752044678)])
Noise:  20
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e420.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [0.42572692, tensor(0.9237)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e420.m',
              0.9237499833106995)])
Noise:  25
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e425.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [29.74483, tensor(0.8648)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e425.m',
              0.8647500276565552)])
Noise:  30
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e430.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [0.51494944, tensor(0.9185)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e430.m',
              0.9185000061988831)])
Noise:  35
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e435.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [0.66567194, tensor(0.8848)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e435.m',
              0.8847500085830688)])
Noise:  40
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e440.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [2.3167746, tensor(0.8217)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e440.m',
              0.8217499852180481)])
Noise:  45
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e445.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Loss and accuracy using (cls_best): [1.6398115, tensor(0.8192)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e445.m',
              0.8192499876022339)])
Noise:  50
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e450.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 4729 examples, only 0.5 have correct labels
Added noise to 500 examples, only 0.5 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.5tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.222034    1.372962    0.382000
2         1.222928    9.350571    0.374000
3         1.200542    1.636571    0.413000
4         1.175799    7.368647    0.417000
Total time: 05:31
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e450.m
Loss and accuracy using (cls_best): [5.1662917, tensor(0.7197)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e450.m',
              0.7197499871253967)])
Noise:  55
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e455.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5201 examples, only 0.4500951575385917 have correct labels
Added noise to 550 examples, only 0.45 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.55tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e455.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.241146    1.574603    0.338000
2         1.220505    3.343982    0.314000
3         1.215406    4.805650    0.381000
4         1.192340    3.459251    0.368000
Total time: 05:16
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e455.m
Loss and accuracy using (cls_best): [4.879584, tensor(0.6900)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e455.m',
              0.6899999976158142)])
Noise:  60
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e460.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5674 examples, only 0.4000845844787482 have correct labels
Added noise to 600 examples, only 0.4 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.6tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e460.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.258633    1.374315    0.319000
2         1.249057    1.935162    0.279000
3         1.235318    8.574917    0.325000
4         1.224898    31.664907   0.356000
Total time: 05:25
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e460.m
Loss and accuracy using (cls_best): [33.578053, tensor(0.5670)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e460.m',
              0.5669999718666077)])
Noise:  65
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e465.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6147 examples, only 0.35007401141890465 have correct labels
Added noise to 650 examples, only 0.35 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.65tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e465.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.259673    1.630593    0.307000
2         1.256428    1.900148    0.237000
3         1.241903    3.709883    0.307000
4         1.218096    1.747542    0.292000
Total time: 05:31
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e465.m
Loss and accuracy using (cls_best): [1.3016428, tensor(0.5238)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e465.m',
              0.5237500071525574)])
Noise:  70
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e470.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6620 examples, only 0.30006343835906113 have correct labels
Added noise to 700 examples, only 0.3 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.7tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e470.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.261316    1.444706    0.331000
2         1.251065    6.526892    0.285000
3         1.232021    19.925491   0.335000
4         1.207373    1.669503    0.329000
Total time: 05:17
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e470.m
Loss and accuracy using (cls_best): [1.6000191, tensor(0.1885)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e470.m',
              0.18850000202655792)])
Noise:  75
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e475.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 7093 examples, only 0.2500528652992176 have correct labels
Added noise to 750 examples, only 0.25 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.75tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e475.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.256266    1.862535    0.346000
2         1.245836    3.535186    0.307000
3         1.222711    5.987287    0.335000
4         1.206070    4.709743    0.322000
Total time: 06:12
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e475.m
Loss and accuracy using (cls_best): [1.847491, tensor(0.1700)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e475.m',
              0.17000000178813934)])
    noise  accuracy
0    0.00   0.95525
1    0.05   0.87975
2    0.10   0.94200
3    0.15   0.91975
4    0.20   0.92375
5    0.25   0.86475
6    0.30   0.91850
7    0.35   0.88475
8    0.40   0.82175
9    0.45   0.81925
10   0.50   0.71975
11   0.55   0.69000
12   0.60   0.56700
13   0.65   0.52375
14   0.70   0.18850

```

## Epochs 8
```
python -m ulmfit eval_noise_resistance --lang=es --size=10 --prefix-name="sl-e8" --model="sp15k/qrnn_nl4.m"  --num-cls-epochs=8 --label-smoothing-eps=0.1
Noise:  0
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e80.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
/home/pczapla/anaconda3/envs/fastaiv1/lib/python3.7/site-packages/torch/utils/cpp_extension.py:152: UserWarning:

                               !! WARNING !!

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Your compiler (c++) may be ABI-incompatible with PyTorch!
Please use a compiler that is ABI-compatible with GCC 4.9 and above.
See https://gcc.gnu.org/onlinedocs/libstdc++/manual/abi.html.

See https://gist.github.com/goldsborough/d466f43e8ffc948ff92de7486c5216d6
for instructions on how to install GCC 4.9 or higher.
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

                              !! WARNING !!

  warnings.warn(ABI_INCOMPATIBILITY_WARNING.format(compiler))
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e80.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.520412    0.696753    0.934000
2         0.509825    0.735629    0.934000
3         0.486594    0.684108    0.931000
4         0.488381    0.579037    0.953000
5         0.471751    0.588278    0.945000
6         0.459802    0.567890    0.943000
7         0.455027    0.545390    0.954000
8         0.462613    0.575517    0.943000
Total time: 11:12
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e80.m
Loss and accuracy using (cls_best): [0.27576917, tensor(0.9417)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e80.m',
              0.9417499899864197)])
Noise:  5
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e85.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 472 examples, only 0.9500951575385916 have correct labels
Added noise to 50 examples, only 0.95 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.05tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e85.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.666560    0.852668    0.874000
2         0.657355    5.546601    0.824000
3         0.656841    7.308374    0.853000
4         0.612917    24.591734   0.790000
5         0.596588    12.358717   0.834000
6         0.568417    4.996921    0.913000
7         0.557468    1.554828    0.831000
8         0.536724    1.115134    0.858000
Total time: 10:51
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e85.m
Loss and accuracy using (cls_best): [0.6382615, tensor(0.9078)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e85.m',
              0.9077500104904175)])
Noise:  10
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e810.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 945 examples, only 0.9000845844787482 have correct labels
Added noise to 100 examples, only 0.9 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.1tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e810.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.771364    0.982115    0.801000
2         0.744242    0.947076    0.840000
3         0.736343    1.086157    0.842000
4         0.730165    0.987014    0.827000
5         0.708371    5.287072    0.763000
6         0.697188    0.855899    0.833000
7         0.640460    0.931902    0.835000
8         0.593337    0.915233    0.837000
Total time: 10:48
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e810.m
Loss and accuracy using (cls_best): [0.45135674, tensor(0.9170)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e810.m',
              0.9169999957084656)])
Noise:  15
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e815.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 1418 examples, only 0.8500740114189046 have correct labels
Added noise to 150 examples, only 0.85 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.15tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e815.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.848943    1.361678    0.751000
2         0.857650    1.120813    0.662000
3         0.861447    1.036685    0.809000
4         0.824053    1.000713    0.786000
5         0.821309    1.111803    0.799000
6         0.754514    1.129427    0.782000
7         0.695773    1.394005    0.765000
8         0.638984    1.081989    0.780000
Total time: 11:00
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e815.m
Loss and accuracy using (cls_best): [0.36475056, tensor(0.9005)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e815.m',
              0.9004999995231628)])
Noise:  20
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e820.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 1891 examples, only 0.8000634383590611 have correct labels
Added noise to 200 examples, only 0.8 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.2tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e820.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.931807    1.271276    0.709000
2         0.923600    1.298985    0.741000
3         0.925085    5.663558    0.658000
4         0.929284    1.188406    0.739000
5         0.888162    3.878520    0.658000
6         0.819503    1.259068    0.731000
7         0.752936    1.150221    0.710000
8         0.735175    1.149028    0.722000
Total time: 11:07
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e820.m
Loss and accuracy using (cls_best): [0.4438091, tensor(0.8813)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e820.m',
              0.8812500238418579)])
Noise:  25
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e825.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 2364 examples, only 0.7500528652992176 have correct labels
Added noise to 250 examples, only 0.75 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.25tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e825.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.999227    1.194783    0.646000
2         0.990589    2.633189    0.626000
3         1.018390    1.542320    0.659000
4         0.987891    7.653442    0.605000
5         0.972299    2.651095    0.646000
6         0.922192    9.360953    0.637000
7         0.878368    2.497859    0.640000
8         0.847166    1.993811    0.639000
Total time: 10:48
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e825.m
Loss and accuracy using (cls_best): [0.88353807, tensor(0.8367)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e825.m',
              0.8367499709129333)])
Noise:  30
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e830.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 2837 examples, only 0.7000422922393741 have correct labels
Added noise to 300 examples, only 0.7 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.3tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e830.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.052917    1.325655    0.581000
2         1.071630    1.998020    0.526000
3         1.063711    31.339291   0.510000
4         1.029802    2.206242    0.607000
5         1.027847    1.763125    0.607000
6         0.961119    1.473439    0.657000
7         0.908768    1.629924    0.617000
8         0.873362    1.462983    0.626000
Total time: 10:44
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e830.m
Loss and accuracy using (cls_best): [0.61362606, tensor(0.8410)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e830.m',
              0.8410000205039978)])
Noise:  35
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e835.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 3310 examples, only 0.6500317191795305 have correct labels
Added noise to 350 examples, only 0.65 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.35tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e835.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.124931    1.301690    0.549000
2         1.098526    1.527998    0.599000
3         1.109146    3.372168    0.557000
4         1.085633    9.049232    0.536000
5         1.040149    2.878901    0.552000
6         0.999970    1.699484    0.548000
7         0.924742    2.458920    0.519000
8         0.916262    5.709455    0.517000
Total time: 10:39
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e835.m
Loss and accuracy using (cls_best): [7.591171, tensor(0.6967)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e835.m',
              0.6967499852180481)])
Noise:  40
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e840.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 3783 examples, only 0.600021146119687 have correct labels
Added noise to 400 examples, only 0.6 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.4tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e840.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.165653    1.350154    0.508000
2         1.172212    1.732053    0.421000
3         1.159003    9.825891    0.476000
4         1.147642    2.909990    0.485000
5         1.085988    4.217392    0.523000
6         1.073084    3.288731    0.488000
7         0.998839    1.664031    0.482000
8         0.932477    1.921165    0.471000
Total time: 11:06
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e840.m
Loss and accuracy using (cls_best): [0.8643208, tensor(0.7275)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e840.m',
              0.7275000214576721)])
Noise:  45
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e845.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 4256 examples, only 0.5500105730598435 have correct labels
Added noise to 450 examples, only 0.55 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.45tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e845.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.195873    1.296093    0.433000
2         1.181843    13.203069   0.375000
3         1.202427    3.895014    0.350000
4         1.180791    2.918823    0.442000
5         1.168890    4.746016    0.477000
6         1.138908    5.763408    0.452000
7         1.085301    1.734959    0.487000
8         1.019007    1.669769    0.467000
Total time: 10:40
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e845.m
Loss and accuracy using (cls_best): [0.99686193, tensor(0.7107)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e845.m',
              0.7107499837875366)])
Noise:  50
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e850.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 4729 examples, only 0.5 have correct labels
Added noise to 500 examples, only 0.5 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.5tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e850.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.206193    1.506727    0.400000
2         1.219487    1.916529    0.383000
3         1.201234    12.136375   0.383000
4         1.193026    2.111413    0.403000
5         1.184301    2.633834    0.438000
6         1.145973    2.558009    0.437000
7         1.099467    2.177719    0.410000
8         1.061634    2.724488    0.401000
Total time: 11:06
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e850.m
Loss and accuracy using (cls_best): [1.8331982, tensor(0.5920)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e850.m',
              0.5920000076293945)])
Noise:  55
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e855.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5201 examples, only 0.4500951575385917 have correct labels
Added noise to 550 examples, only 0.45 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.55tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e855.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.231457    1.337840    0.356000
2         1.245993    12.007490   0.306000
3         1.229736    1.784564    0.331000
4         1.227334    4.005848    0.339000
5         1.207836    12.369584   0.363000
6         1.186945    15.869857   0.365000
7         1.143967    22.024086   0.386000
8         1.097784    4.130466    0.361000
Total time: 10:52
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e855.m
Loss and accuracy using (cls_best): [1.1213393, tensor(0.6237)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e855.m',
              0.6237499713897705)])
Noise:  60
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e860.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5674 examples, only 0.4000845844787482 have correct labels
Added noise to 600 examples, only 0.4 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.6tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e860.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.253129    1.360811    0.344000
2         1.259076    1.422704    0.292000
3         1.249924    2.302250    0.258000
4         1.238938    7.596085    0.318000
5         1.226801    19.490450   0.361000
6         1.220376    45.920719   0.358000
7         1.186902    92.042252   0.361000
8         1.169160    47.323799   0.352000
Total time: 10:51
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e860.m
Loss and accuracy using (cls_best): [54.127697, tensor(0.5253)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e860.m',
              0.5252500176429749)])
Noise:  65
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e865.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6147 examples, only 0.35007401141890465 have correct labels
Added noise to 650 examples, only 0.35 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.65tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e865.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.258576    1.400468    0.285000
2         1.252457    1.485225    0.303000
3         1.264578    15.317787   0.257000
4         1.245918    8.976856    0.300000
5         1.239147    5.338088    0.296000
6         1.226425    8.540084    0.314000
7         1.206139    8.959650    0.300000
8         1.185957    7.868751    0.322000
Total time: 10:47
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e865.m
Loss and accuracy using (cls_best): [3.7213144, tensor(0.5070)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e865.m',
              0.5070000290870667)])
Noise:  70
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e870.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6620 examples, only 0.30006343835906113 have correct labels
Added noise to 700 examples, only 0.3 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.7tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e870.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.257724    1.391102    0.311000
2         1.259833    1.376604    0.346000
3         1.256289    4.146193    0.272000
4         1.248032    21.711473   0.308000
5         1.237731    104.512573  0.287000
6         1.226114    14.212803   0.318000
7         1.190652    3.960902    0.333000
8         1.186640    2.436945    0.339000
Total time: 10:38
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e870.m
Loss and accuracy using (cls_best): [2.232332, tensor(0.2713)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e870.m',
              0.27125000953674316)])
Noise:  75
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e875.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 7093 examples, only 0.2500528652992176 have correct labels
Added noise to 750 examples, only 0.25 have correct labels
Data lm, trn: 13013, val: 1445
Data clsnoise0.75tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e875.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.246185    1.331556    0.343000
2         1.247202    1.593753    0.334000
3         1.248334    4.676108    0.320000
4         1.235685    27.420618   0.289000
5         1.221268    10.798445   0.330000
6         1.201879    4.895516    0.335000
7         1.164162    3.015471    0.353000
8         1.146750    2.903884    0.353000
Total time: 11:04
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e875.m
Loss and accuracy using (cls_best): [3.2696714, tensor(0.1305)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_sl-e875.m',
              0.13050000369548798)])
    noise  accuracy
0    0.00   0.94175
1    0.05   0.90775
2    0.10   0.91700
3    0.15   0.90050
4    0.20   0.88125
5    0.25   0.83675
6    0.30   0.84100
7    0.35   0.69675
8    0.40   0.72750
9    0.45   0.71075
10   0.50   0.59200
11   0.55   0.62375
12   0.60   0.52525
13   0.65   0.50700
14   0.70   0.27125
```


# Correct VAL
```
python -m ulmfit eval_noise_resistance --lang=es --size=10 --prefix-name="val_"
Noise:  0
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_0.m
Evaluating previously trained model
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Data lm, trn: 13013, val: 1445
Data cls, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
/home/pczapla/anaconda3/envs/fastaiv1/lib/python3.7/site-packages/torch/utils/cpp_extension.py:152: UserWarning:

                               !! WARNING !!

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Your compiler (c++) may be ABI-incompatible with PyTorch!
Please use a compiler that is ABI-compatible with GCC 4.9 and above.
See https://gcc.gnu.org/onlinedocs/libstdc++/manual/abi.html.

See https://gist.github.com/goldsborough/d466f43e8ffc948ff92de7486c5216d6
for instructions on how to install GCC 4.9 or higher.
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

                              !! WARNING !!

  warnings.warn(ABI_INCOMPATIBILITY_WARNING.format(compiler))
Loss and accuracy using (cls_last): [0.38580656, tensor(0.9402)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_0.m',
              0.9402499794960022)])
Noise:  5
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_5.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 472 examples, only 0.9500951575385916 have correct labels
Added noise to 50 examples, only 0.95 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.05tv...
Data clsnoise0.05tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_5.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.360209    0.664265    0.831000
2         0.367246    0.505887    0.884000
3         0.339675    0.646535    0.862000
4         0.324250    0.914779    0.849000
5         0.303626    0.592339    0.894000
6         0.225317    0.699065    0.878000
7         0.220272    0.726604    0.868000
8         0.160895    0.767783    0.863000
Total time: 11:24
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_5.m
Loss and accuracy using (cls_best): [0.36014587, tensor(0.9170)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_5.m',
              0.9169999957084656)])
Noise:  10
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_10.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 945 examples, only 0.9000845844787482 have correct labels
Added noise to 100 examples, only 0.9 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.1tv...
Data clsnoise0.1tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_10.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.535271    0.740620    0.824000
2         0.496433    1.023953    0.669000
3         0.474564    0.993422    0.832000
4         0.468398    6.249076    0.785000
5         0.480843    0.850946    0.830000
6         0.395878    0.789419    0.851000
7         0.298389    2.299487    0.823000
8         0.253688    2.279287    0.824000
Total time: 11:21
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_10.m
Loss and accuracy using (cls_best): [0.871454, tensor(0.9075)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_10.m',
              0.9075000286102295)])
Noise:  15
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_15.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 1418 examples, only 0.8500740114189046 have correct labels
Added noise to 150 examples, only 0.85 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.15tv...
Data clsnoise0.15tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_15.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.652501    1.015270    0.741000
2         0.654432    1.025377    0.748000
3         0.617786    1.639322    0.792000
4         0.639355    1.662912    0.747000
5         0.577110    5.244443    0.743000
6         0.527992    3.701031    0.766000
7         0.393420    3.620962    0.759000
8         0.361106    3.019649    0.780000
Total time: 11:31
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_15.m
Loss and accuracy using (cls_best): [0.35248652, tensor(0.9043)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_15.m',
              0.9042500257492065)])
Noise:  20
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_20.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 1891 examples, only 0.8000634383590611 have correct labels
Added noise to 200 examples, only 0.8 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.2tv...
Data clsnoise0.2tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_20.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.749732    1.118057    0.710000
2         0.785584    6.410913    0.607000
3         0.713528    2.003799    0.754000
4         0.752761    2.294566    0.724000
5         0.652672    19.180836   0.708000
6         0.596508    2.582183    0.711000
7         0.489806    2.648639    0.712000
8         0.467246    3.001610    0.698000
Total time: 11:36
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_20.m
Loss and accuracy using (cls_best): [1.6113901, tensor(0.8475)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_20.m',
              0.8475000262260437)])
Noise:  25
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_25.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 2364 examples, only 0.7500528652992176 have correct labels
Added noise to 250 examples, only 0.75 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.25tv...
Data clsnoise0.25tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_25.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.844129    1.047693    0.663000
2         0.810037    1.353432    0.655000
3         0.820446    3.722627    0.632000
4         0.779205    1.445673    0.630000
5         0.770405    1.024933    0.653000
6         0.695584    1.400032    0.676000
7         0.582116    1.612832    0.649000
8         0.542117    1.422031    0.648000
Total time: 11:48
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_25.m
Loss and accuracy using (cls_best): [0.62123287, tensor(0.8300)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_25.m',
              0.8299999833106995)])
Noise:  30
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_30.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 2837 examples, only 0.7000422922393741 have correct labels
Added noise to 300 examples, only 0.7 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.3tv...
Data clsnoise0.3tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_30.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.946058    1.269022    0.625000
2         0.942436    2.030650    0.636000
3         0.920219    5.243942    0.463000
4         0.890941    14.097425   0.605000
5         0.835836    5.551986    0.617000
6         0.708443    2.086009    0.624000
7         0.639320    2.845402    0.582000
8         0.537422    1.683678    0.597000
Total time: 11:21
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_30.m
Loss and accuracy using (cls_best): [0.6909822, tensor(0.7915)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_30.m',
              0.7914999723434448)])
Noise:  35
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_35.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 3310 examples, only 0.6500317191795305 have correct labels
Added noise to 350 examples, only 0.65 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.35tv...
Data clsnoise0.35tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_35.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.980721    1.266943    0.471000
2         0.980537    1.438193    0.492000
3         1.000082    5.081447    0.539000
4         0.964535    1.640518    0.547000
5         0.924568    2.078268    0.588000
6         0.915998    1.612291    0.562000
7         0.790721    1.804647    0.522000
8         0.716465    2.185110    0.520000
Total time: 11:48
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_35.m
Loss and accuracy using (cls_best): [1.8067851, tensor(0.7657)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_35.m',
              0.765749990940094)])
Noise:  40
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_40.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 3783 examples, only 0.600021146119687 have correct labels
Added noise to 400 examples, only 0.6 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.4tv...
Data clsnoise0.4tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_40.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.031590    1.277689    0.458000
2         1.056317    2.782609    0.349000
3         1.044410    1.631716    0.449000
4         1.034872    2.103323    0.478000
5         0.966710    1.642946    0.472000
6         0.943393    1.632070    0.490000
7         0.856185    1.868247    0.479000
8         0.780535    1.958063    0.483000
Total time: 11:36
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_40.m
Loss and accuracy using (cls_best): [0.8928685, tensor(0.7508)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_40.m',
              0.7507500052452087)])
Noise:  45
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_45.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 4256 examples, only 0.5500105730598435 have correct labels
Added noise to 450 examples, only 0.55 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.45tv...
Data clsnoise0.45tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_45.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.064314    1.302667    0.444000
2         1.094542    2.054388    0.439000
3         1.071187    2.209423    0.450000
4         1.077246    6.365521    0.471000
5         1.051128    3.242248    0.406000
6         0.998142    2.802290    0.464000
7         0.918943    2.492715    0.468000
8         0.864835    8.349169    0.457000
Total time: 11:39
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_45.m
Loss and accuracy using (cls_best): [6.738212, tensor(0.6977)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_45.m',
              0.6977499723434448)])
Noise:  50
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_50.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 4729 examples, only 0.5 have correct labels
Added noise to 500 examples, only 0.5 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.5tv...
Data clsnoise0.5tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_50.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.101441    1.358480    0.450000
2         1.150545    1.360492    0.392000
3         1.120479    1.384937    0.437000
4         1.110555    1.345856    0.401000
5         1.089176    1.815834    0.420000
6         1.051251    2.371094    0.422000
7         1.004491    1.379894    0.410000
8         0.936776    1.549806    0.424000
Total time: 11:37
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_50.m
Loss and accuracy using (cls_best): [1.1773515, tensor(0.6180)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_50.m',
              0.6179999709129333)])
Noise:  55
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_55.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5201 examples, only 0.4500951575385917 have correct labels
Added noise to 550 examples, only 0.45 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.55tv...
Data clsnoise0.55tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_55.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.149922    1.401648    0.383000
2         1.144570    9.186795    0.301000
3         1.162765    1.583447    0.330000
4         1.154295    1.568725    0.349000
5         1.117640    1.624917    0.352000
6         1.097049    2.510476    0.362000
7         1.048231    3.798041    0.362000
8         1.020844    3.568361    0.366000
Total time: 11:25
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_55.m
Loss and accuracy using (cls_best): [1.6726145, tensor(0.6102)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_55.m',
              0.6102499961853027)])
Noise:  60
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_60.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5674 examples, only 0.4000845844787482 have correct labels
Added noise to 600 examples, only 0.4 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.6tv...
Data clsnoise0.6tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_60.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.166367    1.629363    0.358000
2         1.175406    1.307703    0.341000
3         1.172992    1.437346    0.342000
4         1.163454    10.670442   0.339000
5         1.158758    2.170272    0.325000
6         1.122279    11.275146   0.351000
7         1.080830    24.562853   0.359000
8         1.055806    19.967308   0.354000
Total time: 11:25
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_60.m
Loss and accuracy using (cls_best): [9.046943, tensor(0.4873)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_60.m',
              0.4872500002384186)])
Noise:  65
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_65.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6147 examples, only 0.35007401141890465 have correct labels
Added noise to 650 examples, only 0.35 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.65tv...
Data clsnoise0.65tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_65.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.188989    1.408018    0.326000
2         1.182579    1.576379    0.279000
3         1.180070    1.482971    0.257000
4         1.164961    1.580750    0.283000
5         1.166036    1.530756    0.294000
6         1.136221    1.670132    0.297000
7         1.102457    2.092621    0.291000
8         1.058724    2.033105    0.287000
Total time: 11:22
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_65.m
Loss and accuracy using (cls_best): [5.145201, tensor(0.4150)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_65.m',
              0.41499999165534973)])
Noise:  70
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_70.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6620 examples, only 0.30006343835906113 have correct labels
Added noise to 700 examples, only 0.3 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.7tv...
Data clsnoise0.7tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_70.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.181723    1.387360    0.342000
2         1.179477    11.148307   0.343000
3         1.178954    2.155812    0.293000
4         1.177750    2.038787    0.308000
5         1.156294    8.581575    0.319000
6         1.122391    1.584792    0.346000
7         1.095312    2.261911    0.346000
8         1.048026    1.873787    0.337000
Total time: 11:40
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_70.m
Loss and accuracy using (cls_best): [2.1144376, tensor(0.2125)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_70.m',
              0.21250000596046448)])
Noise:  75
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_75.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 7093 examples, only 0.2500528652992176 have correct labels
Added noise to 750 examples, only 0.25 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.75tv...
Data clsnoise0.75tv, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_75.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.163953    1.370035    0.298000
2         1.167424    1.883017    0.354000
3         1.145917    1.854918    0.353000
4         1.155910    1.328685    0.329000
5         1.141541    1.895262    0.342000
6         1.091663    22.743765   0.326000
7         1.047826    50.595406   0.315000
8         0.997792    39.199989   0.317000
Total time: 11:30
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_val_75.m
Loss and accuracy using (cls_best): [38.87539, tensor(0.1922)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_val_75.m',
              0.19224999845027924)])
{'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_0.m': 0.9402499794960022, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_5.m': 0.9169999957084656, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_10.m': 0.9075000286102295, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_15.m': 0.9042500257492065, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_20.m': 0.8475000262260437, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_25.m': 0.8299999833106995, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_30.m': 0.7914999723434448, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_35.m': 0.765749990940094, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_40.m': 0.7507500052452087, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_45.m': 0.6977499723434448, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_50.m': 0.6179999709129333, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_55.m': 0.6102499961853027, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_60.m': 0.4872500002384186, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_65.m': 0.41499999165534973, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_70.m': 0.21250000596046448, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_val_75.m': 0.19224999845027924}
```

# Incorrect Val data
```
Noise:  0
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_0.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Running tokenization lm...
Data lm, trn: 13013, val: 1445
Running tokenization cls...
Data cls, trn: 9458, val: 1000
Running tokenization tst...
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
/home/pczapla/anaconda3/envs/fastaiv1/lib/python3.7/site-packages/torch/utils/cpp_extension.py:152: UserWarning:

                               !! WARNING !!

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
Your compiler (c++) may be ABI-incompatible with PyTorch!
Please use a compiler that is ABI-compatible with GCC 4.9 and above.
See https://gcc.gnu.org/onlinedocs/libstdc++/manual/abi.html.

See https://gist.github.com/goldsborough/d466f43e8ffc948ff92de7486c5216d6
for instructions on how to install GCC 4.9 or higher.
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

                              !! WARNING !!

  warnings.warn(ABI_INCOMPATIBILITY_WARNING.format(compiler))
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_0.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.118179    0.265471    0.939000
2         0.131938    0.823511    0.839000
3         0.139424    0.496273    0.906000
4         0.065336    0.315253    0.951000
5         0.050494    0.366971    0.938000
6         0.041825    0.296858    0.965000
7         0.023676    0.330993    0.957000
8         0.014899    0.337952    0.952000
Total time: 11:14
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_0.m
Loss and accuracy using (cls_best): [0.37119418, tensor(0.9465)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_0.m',
              0.9465000033378601)])
Noise:  5
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_5.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 472 examples, only 0.9500951575385916 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.05...
Data clsnoise0.05, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_5.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.381904    0.318090    0.893000
2         0.366108    0.304496    0.907000
3         0.350814    0.222635    0.954000
4         0.305924    0.316391    0.937000
5         0.294849    0.365258    0.938000
6         0.226888    0.265155    0.953000
7         0.203635    0.277920    0.944000
8         0.180686    0.326215    0.935000
Total time: 11:05
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_5.m
Loss and accuracy using (cls_best): [0.31352887, tensor(0.9302)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_5.m',
              0.9302499890327454)])
Noise:  10
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_10.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 945 examples, only 0.9000845844787482 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.1...
Data clsnoise0.1, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_10.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.503315    0.294730    0.903000
2         0.520918    0.404052    0.908000
3         0.496451    0.623593    0.825000
4         0.484413    0.212174    0.950000
5         0.397562    0.271711    0.929000
6         0.393162    0.455898    0.908000
7         0.329386    0.306643    0.922000
8         0.285580    0.283296    0.921000
Total time: 11:17
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_10.m
Loss and accuracy using (cls_best): [0.2845364, tensor(0.9258)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_10.m',
              0.9257500171661377)])
Noise:  15
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_15.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 1418 examples, only 0.8500740114189046 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.15...
Data clsnoise0.15, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_15.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.641261    0.416610    0.848000
2         0.602479    0.356870    0.901000
3         0.652983    0.582720    0.812000
4         0.582735    22.428156   0.942000
5         0.565184    7.965161    0.855000
6         0.489513    0.751756    0.898000
7         0.418973    6.047875    0.859000
8         0.337963    9.058367    0.845000
Total time: 11:23
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_15.m
Loss and accuracy using (cls_best): [11.41559, tensor(0.8332)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_15.m',
              0.8332499861717224)])
Noise:  20
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_20.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 1891 examples, only 0.8000634383590611 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.2...
Data clsnoise0.2, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_20.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.735070    0.430566    0.875000
2         0.777014    1.136241    0.711000
3         0.762944    10.364647   0.624000
4         0.698076    1.523277    0.806000
5         0.646547    1.162918    0.833000
6         0.581218    1.385464    0.869000
7         0.489041    1.207447    0.843000
8         0.398324    0.668090    0.849000
Total time: 11:16
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_20.m
Loss and accuracy using (cls_best): [0.55489075, tensor(0.8595)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_20.m',
              0.859499990940094)])
Noise:  25
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_25.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 2364 examples, only 0.7500528652992176 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.25...
Data clsnoise0.25, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_25.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.877402    0.428968    0.871000
2         0.874461    0.585437    0.772000
3         0.866958    0.598036    0.807000
4         0.805568    0.964052    0.893000
5         0.760956    5.249828    0.800000
6         0.671527    1.038407    0.864000
7         0.597481    0.767250    0.855000
8         0.539228    0.695689    0.853000
Total time: 11:29
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_25.m
Loss and accuracy using (cls_best): [0.61637276, tensor(0.8630)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_25.m',
              0.8629999756813049)])
Noise:  30
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_30.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 2837 examples, only 0.7000422922393741 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.3...
Data clsnoise0.3, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_30.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.908243    0.480479    0.818000
2         0.906832    0.562728    0.773000
3         0.896891    3.017841    0.750000
4         0.900984    2.464900    0.892000
5         0.874264    2.142747    0.833000
6         0.775662    0.491934    0.876000
7         0.614158    0.568567    0.840000
8         0.553789    3.695555    0.797000
Total time: 11:32
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_30.m
Loss and accuracy using (cls_best): [2.999626, tensor(0.7897)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_30.m',
              0.7897499799728394)])
Noise:  35
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_35.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 3310 examples, only 0.6500317191795305 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.35...
Data clsnoise0.35, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_35.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         0.983643    0.519147    0.891000
2         1.010607    0.945973    0.580000
3         0.994139    3.134296    0.461000
4         0.984234    1.258144    0.864000
5         0.923507    9.997900    0.759000
6         0.886210    9.016973    0.667000
7         0.791056    7.744195    0.798000
8         0.683184    4.557703    0.787000
Total time: 11:28
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_35.m
Loss and accuracy using (cls_best): [4.7776446, tensor(0.7642)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_35.m',
              0.7642499804496765)])
Noise:  40
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_40.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 3783 examples, only 0.600021146119687 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.4...
Data clsnoise0.4, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_40.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.029997    0.882142    0.651000
2         1.044314    1.591835    0.618000
3         1.054599    0.522415    0.862000
4         1.033360    0.998230    0.747000
5         1.002742    3.083807    0.803000
6         0.951022    11.693688   0.741000
7         0.859333    4.469426    0.674000
8         0.770237    1.737012    0.712000
Total time: 11:26
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_40.m
Loss and accuracy using (cls_best): [1.721135, tensor(0.7135)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_40.m',
              0.7135000228881836)])
Noise:  45
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_45.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 4256 examples, only 0.5500105730598435 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.45...
Data clsnoise0.45, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_45.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.118304    0.964211    0.720000
2         1.105983    1.031464    0.459000
3         1.090640    1.993658    0.545000
4         1.094765    2.314941    0.550000
5         1.075982    8.962537    0.682000
6         1.044638    4.634834    0.743000
7         0.997964    1.342650    0.711000
8         0.953207    1.860142    0.728000
Total time: 11:14
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_45.m
Loss and accuracy using (cls_best): [2.065772, tensor(0.7682)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_45.m',
              0.7682499885559082)])
Noise:  50
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_50.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 4729 examples, only 0.5 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.5...
Data clsnoise0.5, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_50.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.131220    0.884647    0.677000
2         1.118103    0.786608    0.760000
3         1.135599    1.448700    0.654000
4         1.131183    1.091670    0.655000
5         1.087481    1.086206    0.755000
6         1.071505    47.305462   0.752000
7         1.008586    22.109758   0.724000
8         0.978073    8.738451    0.704000
Total time: 11:20
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_50.m
Loss and accuracy using (cls_best): [7.9533467, tensor(0.6925)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_50.m',
              0.6924999952316284)])
Noise:  55
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_55.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5201 examples, only 0.4500951575385917 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.55...
Data clsnoise0.55, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_55.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.161361    0.962813    0.596000
2         1.150018    1.615359    0.542000
3         1.154646    5.588564    0.572000
4         1.145129    1.064145    0.541000
5         1.138727    0.868817    0.716000
6         1.092911    3.203760    0.673000
7         1.027020    2.577705    0.615000
8         0.962490    2.068990    0.607000
Total time: 11:23
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_55.m
Loss and accuracy using (cls_best): [1.8640332, tensor(0.6400)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_55.m',
              0.6399999856948853)])
Noise:  60
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_60.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 5674 examples, only 0.4000845844787482 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.6...
Data clsnoise0.6, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_60.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.184716    1.159816    0.489000
2         1.162386    1.785291    0.585000
3         1.189221    6.945411    0.523000
4         1.169163    30.551344   0.553000
5         1.143203    96.431221   0.434000
6         1.113257    18.963854   0.475000
7         1.083783    8.783161    0.521000
8         1.064840    7.930975    0.462000
Total time: 11:40
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_60.m
Loss and accuracy using (cls_best): [8.483881, tensor(0.4535)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_60.m',
              0.45350000262260437)])
Noise:  65
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_65.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6147 examples, only 0.35007401141890465 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.65...
Data clsnoise0.65, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_65.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.163443    1.302967    0.355000
2         1.181459    1.265248    0.188000
3         1.189486    6.507479    0.466000
4         1.192368    23.974792   0.525000
5         1.171117    2.516582    0.473000
6         1.139664    1.357649    0.398000
7         1.091899    1.510042    0.437000
8         1.070406    1.511683    0.392000
Total time: 11:29
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_65.m
Loss and accuracy using (cls_best): [1.5956299, tensor(0.3887)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_65.m',
              0.38874998688697815)])
Noise:  70
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_70.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 6620 examples, only 0.30006343835906113 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.7...
Data clsnoise0.7, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_70.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.186880    1.400069    0.164000
2         1.193253    3.277115    0.258000
3         1.173004    2.955142    0.184000
4         1.162564    3.158204    0.105000
5         1.158516    8.930537    0.178000
6         1.117573    25.560179   0.178000
7         1.070933    3.045306    0.183000
8         1.025959    10.724563   0.192000
Total time: 11:31
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_70.m
Loss and accuracy using (cls_best): [9.275186, tensor(0.2153)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_70.m',
              0.21525000035762787)])
Noise:  75
Processing data/mldoc/es-1/models/sp15k/qrnn_nl4.m
es-10
Max vocab: 15000
Cache dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Model dir: /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_75.m
Training
Loading validation /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/es.dev.csv
Added noise to 7093 examples, only 0.2500528652992176 have correct labels
Data lm, trn: 13013, val: 1445
Running tokenization clsnoise0.75...
Data clsnoise0.75, trn: 9458, val: 1000
Data tst, trn: 1000, val: 4000
Size of vocabulary: 15000
First 20 words in vocab: ['xxunk', 'xxpad', 'xxbos', 'xxfld', 'xxmaj', 'xxup', 'xxrep', 'xxwrep', '<unk>', '▁', '▁de', '▁,', '▁la', '▁.', 's', '▁en', '▁el', '▁y', '▁a', '▁que']
Training args:  {'clip': 0.12, 'alpha': 2, 'beta': 1, 'drop_mult': 0.3} dps:  {'output_p': 0.25, 'hidden_p': 0.1, 'input_p': 0.2, 'embed_p': 0.02, 'weight_p': 0.15}
Loading pretrained model
Unknown tokens 0, first 100: []
/home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k
Saving info /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_75.m/info.json
Single training schedule
epoch     train_loss  valid_loss  accuracy
1         1.173947    1.503179    0.149000
2         1.155268    3.008709    0.140000
3         1.166699    4.902722    0.181000
4         1.160365    4.787449    0.190000
5         1.138678    3.777317    0.084000
6         1.071183    3.077753    0.123000
7         1.000427    2.818838    0.166000
8         0.941079    3.680126    0.187000
Total time: 11:42
Saving models at /home/pczapla/workspace/ulmfit-multilingual/data/mldoc/es-10/models/sp15k/qrnn_nl4_75.m
Loss and accuracy using (cls_best): [3.2255151, tensor(0.1877)]
OrderedDict([('data/mldoc/es-10/models/sp15k/qrnn_nl4_75.m',
              0.18774999678134918)])
{'data/mldoc/es-10/models/sp15k/qrnn_nl4_0.m': 0.9465000033378601, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_5.m': 0.9302499890327454, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_10.m': 0.9257500171661377, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_15.m': 0.8332499861717224, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_20.m': 0.859499990940094, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_25.m': 0.8629999756813049, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_30.m': 0.7897499799728394, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_35.m': 0.7642499804496765, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_40.m': 0.7135000228881836, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_45.m': 0.7682499885559082, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_50.m': 0.6924999952316284, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_55.m': 0.6399999856948853, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_60.m': 0.45350000262260437, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_65.m': 0.38874998688697815, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_70.m': 0.21525000035762787, 'data/mldoc/es-10/models/sp15k/qrnn_nl4_75.m': 0.18774999678134918}
````