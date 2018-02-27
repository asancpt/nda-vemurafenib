# NDA-review: Vemurafenib

[신약개발 case studies] 흑색종치료제-Vemurafenib
의학약학  루피D몽키 (2018-02-01 09:28)

그림1. Vemurafenib (상품명: Zelboraf)

RAF (Rapidly Accelerated Fibrosarcoma)는 serine/threonine kinase로서 암세포의 증식을 유발하는 oncogene이다. 이 유전자는 35년 전에 발견되었다[1]. RAF kinase family는 C-RAF, A-RAF, B-RAF로 구성되어 있다.

그림2. RAS-RAF-MAPKinase signaling pathway

특정 growth factor에 의하여 receptor tyrosine kinases (RTK)가 autophosphorylation되면, RAS, RAF signaling이 진행된다. RAF는 RAS의 downstream gene이다. RAS는 평상시에 GDP가 결합된 상태로 존재하다가, phosphorylation되면, RAS-GTP의 activation 상태가 된다. Activation이 되어 많은 암관련 단백질을 활성화시키게 된다.  
2002년도에 Nature에 발표된 보고에 따르면, 많은 암에서 BRAF유전자가 mutation되어 있었다[2]. 이중 가장 많은 mutation이 V600E이다. 이 mutation의 위치는 kinase activity를 조절하는 activation loop에 위치하며, mutation 발생시 kinase activity를 증가시켜, cancer cell의 증식을 가속화시켰다. 이 mutation은 모든 melanoma의 절반 정도에서 발견된다. 암의 종류마다 조금씩 차이가 있다[3]. 
BRAF는 비임상연구를 통해 유망한 암타겟인 것이 증명되었다. 세포실험에서 BRAFV600E oncogene에 의해 melanoma 및 다른 암세포 증식이 촉진되었고, 반대로 BRAFV600E을 없애면 세포 증식이 줄어들었다. 또한 in vivo 실험에서도 증명되었다[4,5].
초기에 많은 논문에서 C-RAF는 RAS의 effector로 알려졌기 때문에, 유망한 암 타겟으로 인식되었다. 그래서 C-RAF를 타겟으로 하는 많은 약물이 개발되었다. C-RAF 저해제로 개발된 Sorafenib (Nexavar;Bayer/Onyx)은 renal/hepatocellular carcinoma의 치료제로 승인되었다[6].

그림3. Sorafenib 구조

Sorafenib에 대한 연구 결과에 따르면, 이 약물은 vascular endothelial growth factor receptor(VEGFR)과 같은 kinase를 저해하기 때문이라고 생각된다. 또한 B-RAFV600E에는 전혀 저해능이 없었다. Sorafenib은 melanoma 환자를 대상으로 한 임상에서 약효가 없었는데, 놀랍게도 이 환자들의 절반이상이 BRAF V600 mutation을 가지고 있었다. 이 결과로 말미암아 B-RAF가 melanoma 타겟으로 여겨지게 된다[7].
Kinase 저해제를 개발하는데 있어, crystal구조는 매우 중요한 정보를 제공한다. RAF kinase의 crystal 구조가 없었기 때문에 selective한 화합물을 합성하기 매우 힘들었다. 그러다가 마침내 2004년에 crystal 구조가 밝혀졌다[8]. 이 정보가 vemurafenib을 개발하는데 결정적이었다.
지금부터 두번으로 나누어서 vemurafenib의 개발과정을 리뷰해보고자 한다.

1. Scaffold-based discovery of kinase inhibitors
Kinase 는 1980년대부터 신약개발의 타겟으로 가장 많이 연구되어 졌고, 현재도 연구되고 있는 타겟이다. 2000년대 초반에 High-Throughput Screening (HTS)을 이용하여 많은 수의 화합물 library를 스크리닝 하였고, kinase activity를 저해하는 여러 개의 compound class를 발견하였다. 예를 들면 quinazolines, amino-pyrimidines, oxindoles 등이 있다. 
하지만 이중에서 BRAF를 저해하는 물질은 없었다.

그림4. 대표적 kinase 저해 scaffold

Plexxikon 회사에서 BRAF inhibitor를 찾기 위하여 scaffold-based approach를 사용하였다. 다음과 같은 chemical properties (MW 150-350Da, fewer than eight hydrogen bond donors and acceptors, few rotatable bonds and relatively high aqueous solubility)를 가진 scaffold 화합물을 검색을 하였다. 
BRAF 활성을 평가하기 위한 biochemical assay가 개발되었다. Kinase family중에서 5개의 다른 kinase가 200uM 농도에서 스크리닝되었다. 이중 3개 이상의 kinase를 저해하는 화합물이 다음 연구로 넘어갔다. 이 방법은 선택성이 좋지않고, 워낙 고농도이기때문에 false-positive의 가능성이 있었다. 이런 이슈는 co-crystallography방법으로 극복되었다.  화합물과 kinase의 co-crystal 구조는 true binding interactions를 확인하였다. 
Hit 238개의 화합물의 co-crystal 분석이 수행되었다. 이중 100여개의 co-crystal이 성공적으로 진행되었다. BRAF crystalization은 지지부진하였지만, PIM1, fibroblast growth factor receptor 1 (FGFR1) crystalization이 중요한 정보를 주었다. 
3차원 구조분석은 원자레벨의 weak interaction이지만, binding interaction정보를 주었다. Co-crystal구조는 hit가 정말로 kinase에 붙는 것을 확인시켜 주었다. 구조정보를 손에 쥐면, 화학자, computational chemists, structural biologist가 모여서 가장 최적의 물질을 디자인하고 합성을 진행하게 된다. Scaffold selection의 중요한 criteria는 chemical group에 의해 치환가능한 자리가 많아야 하며, 기존의 알려진 chemical space와 구별되는 orientation을 가져야 한다.
그리하여 PIM1과의 co-crystal 데이터를 기반으로 3-substituted 7-azaindole이 추가 optimization을 위하여 선택되었다. 이 때 FGFR1과의 co-crystal 구조가 나와서 이를 바탕으로 affinity개선이 좀 더 이루어졌다. 이 후의 optimization은 BRAF 구조정보가 필요하였다
BRAF crystal 구조는 truncated kinase domain의 surface hydrophobic residues를 isosteric hydrophilic amino acids로 바꿈으로써 만들어졌다. 이 방법을 이용하여 100개가 넘는 BRAF와 화합물의 co-crystal 구조를 밝힐 수 있었다. Co-crystallography가 밝혀지면, computational simulation, chemistry와 biological assay가 개발되고 potent하고, selective한 화합물을 개발하는 속도가 엄청 빨라진다. Vemurafenib은 co-crystal구조가 나오고 1년내에 만들어진 물질이다.

그림5. Vemurafenib 구조

2. Vemurafenib 약리작용 규명
Vemurafenib은 2005년에 처음 합성되었다. Vemurafenib은 wild type enzyme에 비하여 BRAFV600E에서 활성이 좋았다. 이것은 화합물이 active form에 선택적으로 결합함을 의미한다. 
비록 biochemical assay에서는 WT에 비하여 BRAFV600E의 선택성이 modest했지만, melanoma 라든지 colorectal cancer cell line에서의 선택성은 이보다 훨씬 컸다. 
Vemurafenib과 MEK inhibitor는 cell proliferation을 억제하지만, 다른 pharmacodynamics 효과를 가졌다. MEK inhibitor는 cellular genotype에 상관없이 ERK phosphorylation을 막았지만, vemurafenib은 BRAF-mutant cell에서의 ERK-phosphorylation만 저해하였다. 특이하게도 많은 WT BRAF cell에서 ERK phosphorylation이 vemurafenib에 의해 유도되었다. 이를 RAF inhibitor paradox라고 일컫는다.
Vemurafenib의 효과는 cell line의 종류에 따라 각기 달랐지만, BRAF의 600번째 아미노산에 변이가 생긴 세포에서 매우 효과적이었다. 특히 BRAFV600E mutation을 가진 melanoma, colorectal cancer, papillary thyroid cancer cell line이 매우 효과적이었다. Vemurafenib에 저항성을 가진 cancer cell line의 subset을 이용하여 resistance mechanism이 현재 연구되고 있다. 흥미롭게도, codon 600자리 외에 mutation이 생기면 오히려 kinase activity가 약해지거나 잃어버린다고 한다.
Purified biochemical assay에서 많은 BRAF mutants가 vemurafenib에 sensitive하였지만, mutant를 발현하는 cell line에서는 효과가 약했다. 왜 이렇게 enzyme결과와 cell 결과가 차이가 날까? 실제 이런일은 비일비재하다. 시험관 결과는 생체 내 조건을 반영하지 못하기 때문이다. BRAF는 CRAF와 heterodimer를 이루는데, 이 같은 heterodimerization이 biochemical assay와 cell에서의 결과가 차이나게 만들었을 것이다.
Vemurafenib에 sensitive한 BRAF-mutant cell lines을 주입하여 tumour xenograft 를 만들어, 경구로 주입했을 때 약효를 확인하였다. 만든 cell lines의 종류마다 약효는 조금씩 차이가 났다. 

3. Behind story
Vemurafenib이 개발에는 한국인 과학자가 깊숙히 관여했다. 미국 버클리대 명예교수인 김성호 박사가 그 주인공이다. 생화학에서 가장 중요한 개발의 하나인 tRNA 구조를 밝힌 세계적 단백질 구조생물학자다. 김 교수는 다국적 제약기업과 시작하지 않고 김 교수의 친구 Joseph Schlessinger PLexxikon 회장과 같은 회사 대표이사 Peter Hirth 등 3명과 함께 이번 신약개발 프로젝트를 개시했다.

그림6. 김성호 박사(출처: google)

한편 vemurafenib의 가능성을 눈치챈 일본 다이이찌 산쿄社가 미국 캘리포니아州 버클리에 소재한 제약기업 플렉스사이콘社(Plexxikon)를 최대 9억3,500만 달러에 인수하였다.
(2편에 계속)
Reference
[1] Rapp, U. R. et al. Structure and biological activity of v-raf, a unique oncogene transduced by a retrovirus. Proc. Natl Acad. Sci. USA 80, 4218–4222 (1983).
[2] Davies, H. et al. Mutations of the BRAF gene in human cancer. Nature 417, 949–954 (2002).
[3] Pollock, P. M. & Meltzer, P. S. A genome-based strategy uncovers frequent BRAF mutations in
melanoma. Cancer Cell 2, 5–7 (2002).
[4] Tuveson, D. A., Weber, B. L. & Herlyn, M. BRAF as a potential therapeutic target in melanoma and other malignancies. Cancer Cell 4, 95–98 (2003).
[5] Hoeflich, K. P. et al. Oncogenic BRAF is required for tumor growth and maintenance in melanoma models. Cancer Res. 66, 999–1006 (2006).
[6] Kane, R. C. et al. Sorafenib for the treatment of unresectable hepatocellular carcinoma. Oncologist 14, 95–100 (2009).
[7] Hauschild, A. et al. Results of a phase III, randomized, placebo-controlled study of sorafenib in combination with carboplatin and paclitaxel as second-line treatment in patients with unresectable stage III or stage IV melanoma. J. Clin. Oncol. 27, 2823–2830 (2009).
[8] Wan, P. T. et al. Mechanism of activation of the RAF-ERK signaling pathway by oncogenic mutations of B‑RAF. Cell 116, 855–867 (2004).


임형석 교수님께

안녕하십니까? 전공의 한성필입니다.

제가 Vemurafenib 에 대한 NDA 케이스 스터디를 2월 23일 금요일에 발표하도록 하겠습니다.

감사합니다.

한성필 올림

NDA 리뷰

# Correspondence

Crizotinib은 워낙 유명하여 자료가 많습니다.
 
기본적으로 US FDA site에 가서 label 및 인허가 관련 문건을 검토해 보십시오.
 
그리고 다음 자료도 도움이 될 것입니다.
 
http://theoncologist.alphamedpress.org/content/19/10/e5.full