# Generic family displaying robustly a fast growth of the number of periodic points

by

Pierre Berger CNRS, Université Sorbonne Paris, France

# Contents

Introduction and statement of the main results 206

1. From parabolic maps to fast growths of the number of periodic points 212

1.1. Smooth rotations and parabolic maps of the circle 213

1.2. Normally hyperbolic fibrations 214

1.3. Conditions implying typicalities of fast growths of the number of periodic points 215

2. Locally dense properties of finitely generated groups of circle diffeomorphisms 219

2.1. Blender and parablender IFS 219

2.2. Density of rotations from blender IFS 222

2.3.  $\lambda$ - blender and  $\lambda$ - parablender IFS 224

2.4. Density of parabolic maps from  $\lambda$ - blender IFS 227

3. Intrinsic definition of  $(\lambda)$ - (para)- blenders 229

3.1. Embedding a semi- group into a normally hyperbolic fibration 229

3.2. Intrinsic definition of  $(\lambda)$ - blender 233

3.3. Intrinsic definition of  $C^{r}$ -  $(\lambda)$ - parablender 236

4. Proof of the main theorems 239

4.1. Theorem A 239

4.2. Theorem B 245

5. Perturbation of families of parabolic circle maps to constant rotations 251

Appendix A. Extrinsic definition of  $(\lambda)$ - blender and  $C^{r}$ -  $(\lambda)$ - parablender 259

References 260

# Introduction and statement of the main results

Given a differentiable self- map  $f$  of a compact manifold  $M$ , we denote by

$$
\mathrm{Per}_n f\coloneqq \{x\in M:f^n (x) = x\}
$$

the set of its  $n$ - periodic points. To study its cardinality, we shall consider the subset  $\mathrm{Per}_n^0 f \subset \mathrm{Per}_n f$  of isolated  $n$ - periodic points. The cardinality of  $\mathrm{Per}_n^0 f$  is invariant under conjugacy. Hence, it is natural to study the growth of this cardinality with  $n$ .

Clearly, if  $f$  is a polynomial map, the cardinality of  $\mathrm{Per}_n^0 f$  is bounded by the degree of  $f^n$ , which grows at most exponentially fast (see the generalization [18]). The first study in the  $C^\infty$ - case goes back to Artin and Mazur [2], who proved the existence of a dense set  $\mathcal{D}$  in  $\mathrm{Diff}^\infty (M)$  formed by diffeomorphisms  $f$  such that the cardinality of  $\mathrm{Per}_n^0 f$  grows at most exponentially fast:

$$
\lim_{n\to \infty}\frac{1}{n}\log \mathrm{Card}\mathrm{Per}_n^0 f< \infty . \tag{AM}
$$

This leads Smale [35] and Bowen [15] to wonder whether a topologically generic diffeomorphism satisfies property (AM). Later, Arnold asked the following problem.

Problem 0.1. (Smale [35], Bowen [15], Arnold [1, Problem 1989- 2]) Can the number of fixed points of the  $n$ th iteration of a topologically generic infinitely smooth self- mapping of a compact manifold grow, as  $n$  increases, faster than any prescribed sequence  $(a_n)_n$  (for some subsequences of time values  $n$ )?

Given  $\infty \geqslant r\geqslant 1$ , we recall that a property is  $C^r$ - topologically generic if it holds true in a countable intersection of open and dense sets of  $C^r (M, M)$ . The topology on the space of  $C^\infty$ - maps is the union of the ones induced by the  $C^r$ - topologies for finite  $r \geqslant 0$ .

Behind this problem is the following basic one: Is there an interesting dynamical property which is valid for any polynomial dynamics but not for a typical differentiable dynamics?

We will see that Problem 0.1 motivated a large number of important contributions and that our first main result complements these to give a complete positive answer when  $\dim M \geqslant 2$ .

However, it is well known that topological genericity is not a so good notion of typicality from the metric viewpoint. Indeed, there are topologically generic subsets of  $\mathbb{R}$  which have Lebesgue measure zero. Another notion of typicality was sketched by Kolmogorov during his plenary talk at the International Congress of Mathematicians in 1954. His student Arnold then formalized it as follows [26], [30].

Definition 0.2. (Arnold's typicality) A property  $(\mathcal{P})$  on the set of  $C^r$  - self- mappings of  $M$  is typical if, for  $k\geq 1$  , with  $B_{k}$  the unit closed ball of  $\mathbb{R}^{k}$  , for a topologically generic  $C^r$  - family  $(f_{p})_{p\in B_{k}}$  of maps  $f_{p}\in C^{r}(M,M)$  , the map  $f_{p}$  satisfies property  $(\mathcal{P})$  for Lebesgue almost every  $p\in B_k$

We recall that  $(f_{p})_{p\in B_{k}}$  is of class  $C^r$  if the map  $(p,z)\mapsto f_p(z)$  is of class  $C^r$  . When  $r< \infty$  , the topology on this space is equal to the uniform  $C^r$  - topology of  $C^{r}(B_{k}\times M,M)$  The topology on the space of  $C^{\infty}$  - families is the one given by the union of those induced by the  $C^{r'}$  - topologies for finite  $r^{\prime}\geq 0$  . In this work, we address the following.

Problem 0.3. (Arnold [1, Problem 1992- 13]) Prove that for a typical smooth selfmap  $f$  of a compact manifold, the cardinality of  $\mathrm{Per}_n f$  grows at most exponentially fast.

This problem inspired Arnold to formulate many related ones [1, Problemas 1994- 47, 1994- 48, 1992- 14]. The second and main result of this article is a negative answer to Problem 0.3 in the finite differentiable case and dimension  $\geq 2$  . Before stating this, let us relate (some of) the long tradition of works on these problems.

In dimension 1, Martens- de Melo- van Strien [32] showed that for any  $\infty \geq r\geq 2$  for an open and dense set  $(^{1})$  of  $C^r$  - maps, the number of periodic points grows at most exponentially fast.

Kaloshin [27] answered a question of Artin and Mazur (in the finitely smooth case) by proving that for a dense set  $\mathcal{D}$  in  $\mathrm{Diff}^r (M)$ $r< \infty$  , the set  $\mathrm{Per}_n f$  is finite for every  $n$  (so equal to  $\mathrm{Per}_n^0 f$  ) and its cardinality grows at most exponentially fast. On the other hand, he proved in [28] that whenever  $2\leq r< \infty$  and  $\dim M\geq 2$  , a locally topologically generic diffeomorphism displays a fast growth of the number of periodic points: there exists a non- empty open set  $U\subset \mathrm{Diff}^r (M)$  , so that for any sequence of integers  $(a_{n})_{n}$  , a topologically generic  $f\in U$  satisfies

$$
\lim_{n\to \infty}\frac{\mathrm{Card}P_n^0(f)}{a_n}\geqslant 1. \tag{★}
$$

This answered positively Problem 0.1 in the case  $\dim M\geq 2$  and  $2\leq r< \infty$  . Later BonattiDiaz- Ficher [13] extended this positive answer to the  $C^1$  - case in dimension  $\geq 3$  . The recent seminal work of Turaev [38] also implies that among  $C^{\infty}$  - surface diffeomorphisms, fast growth of the number of periodic points is locally a topologically generic property.(2)

A new argument will enable us to carry the  $C^{\infty}$ - case in dimension  $\geq 3$  which remained open. More precisely, we will show that for any  $2 \leq r \leq \infty$ , among  $C^{r}$ - diffeomorphisms of manifold of dimension  $\geq 3$  or  $C^{\infty}$ - self- mapppings of surface, the fast growth of the number of periodic points is locally a topologically generic property. This yields a full answer to Problem 0.1, in any regularity  $\infty \geq r \geq 2$  and any dimension (our contribution here is the  $C^{\infty}$ - case).

THEOREM A. Let  $\infty \geq r \geq 2$  and let  $M$  be a compact manifold of dimension  $n$ .

If  $n = 1$ , Property (AM) is satisfied by an open and dense set of  $C^{r}$ - self- mapping.

If  $n \geq 2$ , there exists a (non- empty) open set  $U \subset \operatorname {Diff}^{r}(M)$  so that given any sequence  $(a_{n})_{n}$  of integers, a topologically generic  $f$  in  $U$  satisfies  $(*)$ .

To deal with the  $C^{\infty}$ - case, we will prove in Proposition 1.7, that it suffices to show the local density of dynamics with a normally hyperbolic periodic circle on which the dynamics acts as a smooth rotation. Indeed, such a rotation can be perturbed to a rational one, or equivalently having an iterate equal to the identity, and so by adding a  $C^{r}$ - small sine function of high frequency, we can create a perturbation with plenty of  $n$ - periodic saddle points. In order to show that the dynamics acts as a smooth rotation on such a circle, we will use the Arnold- Herman- Yoccoz Theorem 1.1, which explains that we only have to prescribe a Diophantine property for the rotation number of the circle dynamics. To obtain a Diophantine rotation number, we will give evidence in §2.2 that it suffices to couple a Bonatti- Diaz blender with a north- south dynamics on a normally hyperbolic circle. However, we will use a different argument to obtain such a rotation number, which more sophisticated but generalizable to prove a parametric counterpart of Theorem A.

We will focus on parabolic circle diffeomorphisms: these are diffeomorphisms  $g$  with a unique fixed point  $P$  and which satisfy  $D_{P}g = 1$  and  $D_{P}^{2}g \neq 0$ . Since these are easy to perturb to smooth rotations, we will prove in Theorem 1.8 that it suffices to show the local density of dynamics with a normally hyperbolic periodic circle at which the dynamics is parabolic. To show the local density of such assumptions, we will introduce a new object: the  $\lambda$ - blender in §2.3 and §3.2 and introduce a new dynamical rescaling technique in §2.4 and §4.1.

We will first introduce these new techniques and concepts involving blender (including their para version) in the easier setting of IFS defined by a semi- group of circle diffeomorphisms in §2. Recall that given a finite alphabet  $\mathcal{A}$ , the semi- group spanned by  $(g^{\alpha})_{\alpha \in \mathcal{A}} \in \operatorname {Diff}^{\infty}(\mathbb{R} / \mathbb{Z})^{\mathcal{A}}$  is

$$
\langle g^{\alpha}:\alpha \in \mathcal{A}\rangle \coloneqq \{g^{m}\coloneqq g^{m_{n}}\circ \dots \circ g^{m_{1}}:m = (m_{i})_{1\leqslant i\leqslant n}\in \mathcal{A}^{n},n\geqslant 0\}
$$

An immediate consequence of Proposition 2.7 and Corollary 2.15 stated in §2.2 and §2.4 is the following.

COROLLARY A. For a finite set  $\mathcal{A}$ , there is a subset  $D \subset \operatorname{Diff}^{\omega}(\mathbb{R} / \mathbb{Z})^{\mathcal{A}}$  satisfying the following properties:

(1) Every  $(g^{\alpha})_{\alpha \in \mathcal{A}} \in D$  spans a semi-group which contains parabolic maps and smooth rotations. $^{(3)}$ (2) For any  $2 \leqslant r \leqslant \infty$  or  $r = \omega$ , the set  $D$  is  $C^{r}$ -locally dense: its closure has nonempty interior.

These methods might also be also useful to prove that the bifurcation locus of some semi- groups of rational maps arising in Ising models have non- empty interior. $^{(4)}$  We will explain below how this is corollary might be also interesting to extend the concept of universal semi- group [4].

The study of circle diffeomorphisms (and more precisely non- singular flows on the 2- torus) was certainly the original motivation of Kolmogorov to introduce his new notion of typicality. Indeed, Morse- Smale is an open and dense (and so topologically generic) property among circle diffeomorphisms but is not typical in the sense of Arnold. This was proved by Kolmogorov by introducing the KAM theory (in which the Arnold- Herman- Yoccoz Theorem 1.1 belongs).

KAM theory was already implemented to establish fast growth of the number of periodic points for conservative. $^{(5)}$  dynamical systems. Indeed, an immediate consequence of Gelfreich- Turaev theorem [19] is that a locally tologically generic conservative diffeomorphism of surface displays a fast growth of the number of periodic points. $^{(6)}$  More recently, Asaoka [3] used also KAM theory to show the existence of an open set $^{(7)}$  of conservative  $C^{\infty}$ - surface diffeomorphisms in which typically in the sense of Arnold, a map displays a fast growth of the number of periodic points.

While Asaoka gave a negative answer to the conservative counterpart of Arnold's Problem 0.3, in the (original) dissipative setting the trend was more in favor of a positive answer. Indeed, Hunt and Kaloshin [30], [29] used a method described in [20] to show that for  $\infty \geqslant r > 1$ , a prevalent  $C^{r}$ - diffeomorphisms satisfies:

$$
\lim_{n\to \infty}\frac{\log P_n(f)}{n^{1 + \delta}} = 0\quad \mathrm{for~all~}\delta >0. \tag{O}
$$

The notion of prevalence was introduced by Hunt, Sauer and Yorke [25]. A property is prevalent if roughly speaking almost all perturbations in the embedding of a Hilbert cube at every point of a Banach manifold (like  $C^{r}(M,M)$ ), the property holds true. We notice that  $(\diamond)$  is satisfied for a prevalent diffeomorphism but not for a topologically generic diffeomorphism (see other examples of mixed outcome in [24]).

However, the latter did not completely solve Arnold's Problem 0.3, in particular because the notion of prevalence is a priori independent to the notion of typicality initially meant by Arnold. Indeed, his problem was formulated for typicality in the sense of Definition 0.2 (see the explanation after Problem 1.1.5 in [30]). In this term, the second and main result of this work is surprising since it provides a negative answer to Arnold's Problem 0.3 in the case of finite smoothness.

THEOREM B. Let  $\infty \times r\geqslant 1$  and  $0\leqslant k< \infty$  and let  $M$  be a manifold of dimension  $\geqslant 2$  . Then, there exists a (non- empty) open set  $\widehat{U}$  of  $C^{r}$  - families  $(f_{p})_{p\in B_{k}}$  of  $C^{r}$  - selfmappings  $f_{p}$  of  $M$  so that for any sequence of integers  $(a_{n})_{n}$  , a topologically generic  $(f_{p})_{p}\in \widehat{U}$  consists of maps  $f_{p}$  satisfying  $(\star)$  , for every  $p$  in the ball  $B_{k}$  . Moreover,if  $\dim M\geqslant 3$  , the set  $\widehat{U}$  contains families of diffeomorphisms.

We will prove this theorem by basically following the same scheme as for Theorem A. We will show that it suffices to construct a locally dense set  $\widehat{D}$  of families of dynamics  $(f_{p})_{p}$  which are normally hyperbolic at a fibration by circles and display the following property:

$(\widehat{\mathcal{P}})$  There is a finite covering  $(U_{i})_{i}$  of  $B_{k}$  by open subsets  $U_{i}$  of parameters  $p$  for which  $f_{p}$  acts on a periodic fiber as a parabolic dynamics.

Theorem 1.9 asserts that if such a locally dense set  $D$  exists, then a topologically generic family in the interior of the closure  $\operatorname {cl}(D)$  of  $D$  displays a fast growth of the number of periodic points at every parameter, as claimed in Theorem B. The proof of Theorem 1.9 is similar to its parameter- free version (Theorem 1.8), but will need moreover Theorem 1.4 stating that a family of parabolic maps can be smoothly approximated by one having a Diophantine rotation number. The proof of Theorem 1.4 will occupy the whole of §5. The techniques of this latter proof might be generalized to describe the geometry of the parameter space of analytic circle diffeomorphisms, and more precisely how the 1- codimensional manifolds formed the parabolic maps are analytically accumulated by those formed by Diophantine rotations, as seen numerically nearby Arnold tongues.

To prove the local density of families of dynamics satisfying  $(\widehat{\mathcal{P}})$ , we will introduce a new object: the  $C^{r}$ -  $\lambda$ - parablender. It is a generalization of both the  $\lambda$ - blender and the  $C^{r}$ - parablender introduced in [8]. Again its IFS counterpart will be first introduced in §?? and §?? since easier to understand. It is possible to use them to obtain a parametric

version of Corollary A. We will focus on their counterpart for families of differentiable dynamics of a manifold. In §3.3 we will give the intrinsic definition of  $C^r$ - ( $\lambda$ )- parablender as embedded into a normally hyperbolic fibration for a family of differentiable maps. In the appendix we will give an extrinsic definition of them. In §4.2, we will give the parametric counterpart of the argument of §4.1 to achieve the proof of Theorem B.

To conclude this introduction, let me recall that Arnold's philosophy was not to propose problems of binary type admitting a "yes- no" answer, but rather to propose wide- scope programs of explorations of new mathematical (and not only mathematical) continents, where reaching new peaks reveals new perspectives, and where a preconceived formulation of problems would substantially restrict the field of investigations that have been caused by these perspectives. [...] Evolution is more important than achieving records, as he explained in his preface [1].

In this sense the contrast between the result of Kaloshin- Hunt and Theorem B is interesting since they shed light on how an answer to a question might depend on the definition of typicality.

Let us emphasize that the  $C^{\infty}$ - case of Problem 0.3 (or [1, Conjecture 1994- 47]) remains open, although in view of Theorem B, we would bet for a negative answer. we would even dare to propose the following.

Conjecture 0.4. For every  $r\in \{1,\dots,\infty ,\omega \}$ , there exists an open set of diffeomorphisms  $U\in \operatorname {Diff}^r (M)$ , so that given any  $k\geq 0$ , for any  $C^r$ - generic family  $(f_p)_{p\in \mathbb{R}^k}$  with  $f_p\in U$ , for every  $p$  small, the growth of the number of periodic points of  $f_p$  is fast.

In favor of this conjecture, there is the local density of conservative analytic maps satisfying  $(\star)$  [3]. Also, Corollary 4.11 of the proof of Theorem A shows the local density of analytic dynamics with a normally hyperbolic periodic circles at which the dynamics is a smooth Diophantine rotation. We explain there that modulo a solution of Problem 4.12, this implies the existence of a locally dense of analytic (non- conservative) dynamics displaying a fast growth of the number of periodic points. Note that a positive answer to Conjecture 0.4 would give one of the very first example of an interesting property satisfied for a typical analytic map of a compact manifold but not for a polynomial.

Also, Corollary A should be useful to prove the typicality of dynamics with universal behaviors. Indeed, parabolic maps and rotations were used in [5], [16] to show the existence of finitely generated groups containing any prescribed countable subset of  $\operatorname {Diff}^{\infty}(\mathbb{R} / \mathbb{Z})$ . This leads to:

Conjecture 0.5. There exists a finite set  $\mathcal{A}$  such that for any countable subset  $C\subset \operatorname {Diff}^{\infty}(\mathbb{R} / \mathbb{Z})$ , there exists  $D\subset \operatorname {Diff}^{\infty}(\mathbb{R} / \mathbb{Z})^{\mathcal{A}}$  such that

(1) if  $(g^{\alpha})_{\alpha \in \mathcal{A}}\in D$ , the semi-group  $\langle g^{\alpha}:\alpha \in \mathcal{A}\rangle$  contains  $C$ ;

(2) for every  $2 \leqslant r \leqslant \infty$ , the set  $D$  is  $C^r$ -locally dense:  $\operatorname {int} \operatorname {cl}(D) \neq \emptyset$ .

This conjecture applied with  $C$  equal to a dense subset of  $\operatorname {Diff}^\infty (\mathbb{R} / \mathbb{Z})$  would imply that a locally topologically generic free semi- group of circle diffeomorphisms is dense in  $\operatorname {Diff}^\infty (\mathbb{R} / \mathbb{Z})$ . This can be seen as a global version of the main result of Asaoka- Shinohara- Turaev [4] on universality of locally topologically generic free semi- group of interval diffeomorphisms. Universal semi- group are roughly speaking those which contain a dense set of germs of diffeomorphisms. The concept of universality helped Turaev [37] to claim that a global understanding of most of the differentiable dynamics is impossible. However, this claim can be attacked by arguing that the domains of the germs might be "too small to be seen". It is not anymore the case with the above global formulation, which can be certainly generalized in higher dimensions.

Also, the techniques and notions introduced in §2 should lead to a natural parametric counterpart of Corollary A, and so Conjecture 0.5. Such would be helpful to prove [10, Conjecture II.5] stating roughly speaking that among dynamical systems of high- dimensional manifolds, any property which is local and locally topologically generic is then locally typical in the sense of Arnold. The latter conjecture was motivated by our program on emergence [9].

Acknowledgment. I am thankful to Abed Bounemoura, Håkan Eliasson, Bassam Fayad, Vadim Kaloshin, Rafaël Krikorian and Frédéric Le Roux for our interesting conversations. I am grateful to Sylvain Crovisier and Enrique Pujals for our inspiring discussions and Dimitry Turaev for his important comments on the parabolic renormalization for circle diffeomorphisms. I thank Masayuki Asaoka for pointing me a minor mistake in a lemma, Romain Dujardin for his advice on the introduction and Sébastien Biebler for his careful proofreading of the whole manuscript. I thanks the referees for their advices. The author was partially supported by the ERC project 818737 Emergence of wild differentiable dynamical systems.

# 1. From parabolic maps to fast growths of the number of periodic points

In this section we show that in order to prove Theorems A and B, it suffices to construct a normally hyperbolic fibration by circles, at which a dense set of perturbations act parabolically on some periodic fibers. This is stated in Theorems 1.8 and 1.9. The statements and the proof of these theorems need a few results. First, we recall the notion of Poincaré rotation number and Arnold- Herman- Yoccoz Theorem 1.1 in the next subsection. In §1.1, we will recall the notion of parabolic map and state our new Theorem 1.4 on perturbations of families of parabolic maps which are smooth rotations. Then, we

will recall Hirsch- Pugh- Shub Theorem 1.6 and its counterpart for endomorphisms on the persistence of normally hyperbolic fibration. In the last §1.3 we will state and prove Theorems 1.8 and 1.9.

# 1.1. Smooth rotations and parabolic maps of the circle

Given a homeomorphism  $g\in \mathrm{Diff}^0 (\mathbb{R} / \mathbb{Z})$  of the circle  $\mathbb{R} / \mathbb{Z}$  , one defines its rotation number  $\rho_{g}$  as follows. We fix a lifting  $G\in \mathrm{Diff}^0 (\mathbb{R})$  of  $g$  for the covering  $\pi \colon \mathbb{R}\to \mathbb{R} / \mathbb{Z}$  .Then, Poincare proved that the limit  $\begin{array}{r}\rho_{G} = \lim_{n\to \infty}G^{n}(0) / n \end{array}$  is well defined and its projection  $\rho_{g} = \pi (\rho_{G})$  does not depend on the lifting  $G$  of  $g$  . The rotation number of  $g$  is  $\rho_{g}$  . It is easy to show that the rotation number depends continuously on  $g$  . The number  $\rho_{g}\in \mathbb{R}$  is Diophantine, if there exist  $\tau >0$  and  $C > 0$  such that

$$
|q\rho_{g} - p|\geqslant Cq^{-\tau}\quad \mathrm{for~all~}p,q\in \mathbb{N}\backslash \{0\} .
$$

Let us recall that the set of Diophantine numbers is of full Lebesgue measure. Here is Yoccoz' improvement of Herman's theorem of the Arnold conjecture.

THEOREM 1.1. (Arnold- Herman- Yoccoz [21], [39]) If the rotation number  $\rho$  of  $g\in$ $\mathrm{Diff}^{\infty}(\mathbb{R} / \mathbb{Z})$  is Diophantine, then  $g$  is conjugate to the rotation  $R_{\rho}$  of angle  $\rho$  via  $h\in$ $\mathrm{Diff}^{\infty}(\mathbb{R} / \mathbb{Z})$  ..

$$
h\circ g\circ h^{-1} = R_{\rho}.
$$

Moreover, if  $(g_{p})_{p}$  is a  $C^{\infty}$  - family of diffeomorphisms with constant rotation number  $\rho$  which is Diophantine, then  $(g_{p})_{p}$  is conjugate to  $R_{\rho}$  via a  $C^{\infty}$  - family  $(h_{p})_{p}$  of diffeomorphisms  $h_{p}$  ..

$$
h_{p}\circ g_{p}\circ h_{p}^{-1} = R_{\rho}.
$$

Proof. The first part of this theorem is the main result of [39]. Since the conjugacy is uniquely defined up to a composition with a rotation, the second part of this theorem is a local problem. Hence, by the first part, it suffices to show that if  $(g_{p})_{p}$  satisfies moreover  $g_{0} = R_{\rho}$  , then the family of conjugacy  $(h_{p})_{p}$  can be chosen smooth in a neighborhood of  $p = 0$  . This is a direct consequence of [14, Theorem 3.1.1].

A key new idea in this work is to exhibit circle diffeomorphisms with Diophantine rotation number by creating first parabolic diffeomorphisms of the circle.

Definition 1.2. A  $C^2$  - diffeomorphism  $g$  of a circle  $\mathbb{R} / \mathbb{Z}$  is parabolic if it displays a unique fixed point  $p\in \mathbb{R} / \mathbb{Z}$  , and this fixed point is non- degenerate parabolic:

$$
g(p) = p,\quad D_{p}g = 1,\quad D_{p}^{2}g\neq 0.
$$

Using parabolic maps to obtain dynamics smoothly conjugate to Diophantine rotations might sound anti- intuitive, since their rotation number are of two very different kind. Nevertheless the interest of parabolic maps of the circle is that they have a simple geometric definition and are easy to perturb to irrational rotations. Indeed, if  $g$  is a  $C^r$  - parabolic circle map, for  $r\geq 2$  , then its rotation number is zero. By reversing the circle orientation if necessary, we may assume that  $D_p^2 g > 0$  . Then,  $g$  has a lifting  $G$  such that  $x\in \mathbb{R}\mapsto G(x) - x$  is non- negative and less than 1. Thus, for every  $\epsilon >0$  , the lifting  $x\in \mathbb{R}\mapsto G(x) - x + \epsilon$  of the composition  $R_{\epsilon}\circ g$  takes its value in  $(0,1)$  , and so  $R_{\epsilon}\circ g$  has no fixed point, and hence a non- zero rotation number. Then, by continuity of the rotation number and density of Diophantine numbers in  $\mathbb{P}$  , we can choose  $\epsilon >0$  arbitrarily small so that the rotation number  $\rho (\epsilon)$  of  $R_{\epsilon}\circ g$  is Diophantine. This proves the following.

PROPOSITION 1.3. For every  $r\geq 2$  , the set  $D^{r}$  of  $C^r$  - circle maps with Diophantine rotation number accumulates on the set  $P^{r}$  of  $C^r$  - parabolic maps:  $\operatorname {cl}(D^r)\supset P^r$

The above argument is topological. Hence, the following is a non- trivial extension of the latter proposition for parameter families.

THEOREM 1.4. Let  $k\in \mathbb{N}$  and let  $B^{\prime}\in B\subset \mathbb{R}^{k}$  be open subsets. Given any  $C^{\infty}$  - family  $(g_{p})_{p\in B}$  of circle maps such that for every  $p\in B$  the map  $g_{p}$  is parabolic, there exist an arbitrarily small Diophantine number  $\alpha >0$  and a small  $C^{\infty}$  - perturbation  $(\tilde{g}_{p})_{p\in B}$  of  $(g_{p})_{p\in B}$  such that the rotation number of  $\tilde{g}_{p}$  is  $\alpha$  for every  $p\in B^{\prime}$

The proof this theorem will be done in §5 using a parabolic renormalization.

# 1.2. Normally hyperbolic fibrations

Let  $2\leq r\leq \infty$  , let  $f$  be a  $C^r$  - differentiable map of a manifold  $M$  . The proofs of Theorems A and  $\mathrm{B}$  involve a continuous family  $(L_{y})_{y\in \Sigma}$  of disjoint,  $C^r$  - embedded submanifolds  $L_{y}\subset$ $M$  , indexed by a compact set  $\Sigma$  . This defines a fibration  $\textstyle {\mathcal{L}} = \bigcup_{y\in \Sigma}L_{y}\to \Sigma$  . The map  $f\in C^{r}(M,M)$  leaves invariant the fibration  $L$  if, for every  $y\in \Sigma$  , there exists  $\sigma (y)\in \Sigma$  such that  $f$  sends  $L_{y}$  into  $L_{\sigma (y)}$  . Hence, the following diagram commutes:

$$
\begin{array}{r}\mathcal{L}\xrightarrow{f}\mathcal{L}\\\bigg\downarrow\qquad\bigg\downarrow\\\Sigma\xrightarrow{\sigma}\Sigma,\end{array}
$$

Then, observe that  $Df$  leaves invariant the tangent bundle of the fibers  $\begin{array}{r}T\mathcal{L}\coloneqq \bigcup_{y\in \Sigma}TL_{y} \end{array}$  Hence the action  $[Df]$  of  $Df$  on the normal bundle  $\mathcal{N} = (TM|\mathcal{L}) / T\mathcal{L}$  is well defined.

Definition 1.5. For  $R\geqslant 1$  , an  $f$  - invariant fibration  $c$  is  $R$  - normally hyperbolic if  $[D f]$  leaves invariant a splitting  $E^{s}\oplus E^{u} = \mathcal{N}$  ..

$$
[D f](E^{s})\subset E^{s}\quad \mathrm{and}\quad [D f](E^{u})\subset E^{u};
$$

there exists  $N\geqslant 1$  such that, for all unit vectors  $v_{s}\in E^{s}$ $v_{u}\in E^{u}$  , and all  $v\in T L$

$$
\begin{array}{r}{\| [D f^{N}](v_{s})\| < 1,\| [D f^{N}](v_{u})\| >1\mathrm{~and~}\| [D f^{N}](v_{u})\| >\| D f^{N}(v)\|^{R} > \| [D f^{N}](v_{s})\| .} \end{array}
$$

The dynamics is  $R$  - normally expanding at  $c$  if  $E^{s} = 0$

Normally hyperbolic fibrations are important since they are persistent.

THEOREM 1.6. ([22], [7]) Let  $r\geqslant 1$  and  $1\leqslant R\leqslant r$  . Let  $f$  be a  $C^{r}$  - map of  $M$  which is  $R$  - normally hyperbolic at the bundle  $\textstyle{\mathcal{L} = \bigcup_{y\in \Sigma}L_{y}}$  . Moreover, if  $f$  is not a diffeomorphism, we assume that  $f$  is  $R$  - normally expanding at  $c$  . Then, for any  $C^{r}$  - perturbation  $\tilde{f}$  of  $f$  , there exists a continuous family  $(\tilde{L}_{y})_{y\in \Sigma}$  of disjoint  $C^{r}$  - submanifolds such that

$\tilde{f} (\tilde{L}_{y}) = \tilde{L}_{\sigma (y)}$  for every  $y\in \Sigma$  .  $\tilde{L}_{y}$  is  $C^{r}$  - close to  $L_{y}$  for every  $y\in \Sigma$

For our purposes, the map  $\sigma$  of  $\Sigma$  will be conjugate to a full shift  $\sigma$  on a finite alphabet  $\mathcal{A}$  . Then, for a dense set of  $y\in \Sigma$  , the fiber  $L_{y}$  is  $q$  - periodic:  $f^{q}(L_{y}) = L_{y}$  for some  $q\geqslant 1$

# 1.3. Conditions implying typicalities of fast growths of the number of periodic points

We recall that a map  $f$  of a circle is a  $C^{r}$  - rotation if there is  $\alpha \in \mathbb{R} / \mathbb{Z}$  such that  $f$  is  $C^{r}$  conjugate to the rotation  $R_{\alpha}$  of angle  $\alpha$  . The following will be used to prove Theorem A.

PROPOSITION 1.7. Let  $2\leqslant r\leqslant \infty$  and  $U$  be a non- empty subset of  $C^{r}(M,M)$  . Assume that there is a dense set  $D\subset U$  formed by maps  $f$  displaying a  $q$  - periodic, normally hyperbolic,  $C^{r}$  - circle  $\mathbb{T}\subset M$  such that  $f^{q}|_{\mathbb{T}}$  is a  $C^{r}$  - rotation. Then, for any  $(a_{n})_{n}\in \mathbb{N}^{\mathbb{N}}$  a topologically generic  $f\in U$  satisfies

$$
\lim_{n\to \infty}\sup_{a_{n}}\mathrm{Card}\mathrm{Per}_{n}^{0}(f)\geqslant 1.
$$

Proof. Let  $f\in D$  and  $\mathbb{T}$  be as in the statement. Let  $q\geqslant 1$  be the minimal period of  $\mathbb{T}$  ..  $f^{j}(\mathbb{T})$  is disjoint from  $\mathbb{T}$  for every  $1\leqslant j< q$  . Thus, there exists a small  $C^{r}$  - perturbation  $\tilde{f}$  of  $f$  , the map  $\tilde{f}^{q}$  leaves invariant  $\mathbb{T}$  and  $\tilde{f}^{q}|_{\mathbb{T}}$  is a  $C^{r}$  - rational rotation. Then, there exists a  $q^{\prime}\in q\mathbb{N}\backslash \{0\}$  minimal such that  $\tilde{f}^{q^{\prime}}$  leaves invariant  $\mathbb{T}$  , and  $\tilde{f}^{q^{\prime}}|_{\mathbb{T}} = \mathrm{id}_{\mathbb{T}}$  . Observe that  $q^{\prime}$  must be large when  $\tilde{f}$  is close to  $f$

Also, there exist non- trivial segments  $J\in I\subset \mathbb{T}$  such that  $(\tilde{f}^{i}(I))_{1\leqslant i\leqslant q}$  is a disjoint family. Let  $\rho \in C^{\infty}(\mathbb{T},[0,1])$  be a function supported by  $I$  and satisfying  $\rho |_{J} = 1$  .We handle a small perturbation  $\tilde{f}^{\prime}$  of  $\tilde{f}$  supported by a small neighborhood of  $I$  and in the complement of  $\textstyle \bigcup_{1\leqslant k< q}\tilde{f}^{k}(I)$  such that  $(\tilde{f}^{\prime})^{q}|_{J} = x\in J\mapsto x + \epsilon \rho (x)\sin (2\pi \cdot a_{q}\cdot x / |J|)$  for an identification of  $\mathbb{T}$  with  $\mathbb{R} / \mathbb{Z}$  such that the left endpoint of  $J$  is zero and  $\epsilon >0$  is small.

Note that  $\tilde{f}^{\prime}$  displays at least  $a_{q}$  hyperbolic periodic points of period  $q$ . By normal hyperbolicity, these periodic points are hyperbolic, and so persist for small perturbations of  $\tilde{f}^{\prime}$ .

This proves, for every  $N\geqslant 1$  , the existence of an open and dense set  $U_{N}\subset U$  formed by maps  $f\in U_{N}$  displaying at least  $a_{q}$  hyperbolic periodic points of period  $q$  for a certain  $q\geq N$  . The topologically generic set is  $\begin{array}{r}\mathcal{R}\coloneqq \bigcap_{N\geqslant 0}U_N \end{array}$  . As hyperbolic  $q$  - periodic points are isolated in the set of  $q$  - periodic points, for every  $f\in \mathcal{R}$  , there exists  $q$  arbitrarily large such that  $\mathrm{Card}\mathrm{Per}_q^0 f\geqslant a_q$

Although, by KAM theory, it sounds very intuitive that for many normally hyperbolic circle bundles, the hypothesis of the above proposition holds true. Nevertheless, this intuition is not satisfied on a topologically generic set. Indeed, an open and dense set of  $C^{rr}$ - diffeomorphisms of the circle are Morse- Smale. As the set of periodic fibers in a normally hyperbolic bundle is countable, a subset  $D$  of dynamics satisfying the hypotheses of Proposition 1.7 must be topologically meager in  $C^{r}(M, M)$ !

To show that the existence of a set  $D$  satisfying the hypotheses of Proposition 1.7 we will introduce a technique which uses a Bonatti- Diaz blender and a robust heterodimensional cycle. Actually, we are going to prove an equivalent statement to these hypotheses, but more convenient to be used in for the parameter counterpart Theorem B of Theorem A. Here is the statement.

THEOREM 1.8. Let  $2\leqslant r\leqslant \infty$  and  $D\subset C^{r}(M,M)$  the subset of maps  $f$  displaying a  $q$  - periodic, normally hyperbolic,  $C^{r}$  - circle  $\mathbb{T}\subset M$  such that  $f^{q}|_{\mathbb{T}}$  is parabolic. Then, for any  $(a_{n})_{n}\in \mathbb{N}^{\mathbb{N}}$  , a topologically generic  $f$  in the interior of  $d(D)$  satisfies

$$
\lim_{n\to \infty}\sup_{a_n}\frac{1}{a_n}\operatorname {Card}\operatorname{Per}_n^0 (f)\geqslant 1.
$$

Proof. Let us show that we may assume that  $f^{q_i}|\mathbb{T}$  is of class  $C^{\infty}$ . First note that the submanifold  $\mathbb{T}$  is  $r$ - normally hyperbolic. Thus, by [22, § Forced smoothness], it is of class  $C^{r}$ . Therefore, up to a  $C^{r}$ - coordinate change, we may assume that  $\mathbb{T}$  is of class  $C^{\infty}$ . Let  $C\in \mathbb{T}$  be the parabolic periodic point and let us identify  $\mathbb{T}$  with  $\mathbb{R} / \mathbb{Z}$ . Note that  $x\in \mathbb{T}\mapsto f^{q}(x) - x$  is a unimodal map nearby  $C$  and zero is its unique critical value. We now perform a smoothing of  $f$  such that  $\mathbb{T}$  remains  $q$ - periodic. Note that the induced perturbation of  $x\in \mathbb{T}\mapsto f^{q}(x) - x$  is still unimodal nearby  $C$  with a small critical

value. Thus, by composing with a small local translation along this fiber, we can restor the critical value to zero. We obtained a  $C^{r}$ - perturbation of  $f$  whose  $q_{i}$  iterate leaves invariant  $\mathbb{T}$ , and its restriction at it is both parabolic and of class  $C^{\infty}$ .

Then, Proposition 1.3 implies the existence of a  $C^{r}$ - perturbation at which the dynamics on the normally hyperbolic, periodic,  $C^{\infty}$ - circle displays a Diophantine rotation number. Therefore, by Yoccoz' Theorem 1.1, the dynamics on the normally hyperbolic, periodic,  $C^{\infty}$ - circle is ( $C^{\infty}$ - conjugated to) an irrational rotation. Then, Proposition 1.7 implies the sought result.

Theorem A will be proved by showing that the assumptions of Theorem 1.8 are satisfied. In order to do so, we will introduce a new object, the  $\lambda$ - blender. This object will be coupled to a north- south dynamics of the circle. Then, a new technique involving a dynamical rescaling will reveal the density of the parabolic maps. These concepts and techniques will be first introduced in the context of semi- group of circle maps in §2, then the  $\lambda$ - blender IFS will be embedded in a normally hyperbolic fibration in §3.1 and §3.2, and used in §4.1 to prove Theorem A.

In parallel to the proof Theorem A, we will introduce the parametric counterpart of each studied object. The parametric counterpart of the  $\lambda$ - blender will be the  $\lambda$ -  $C^{r}$ - parablender. It will be introduced in §2 for semi- groups of families of maps, and then generalized for skew products over a shift in §3.3. This will be used in §4.2 to prove Theorem B, by proving that the assumptions of the next theorem are satisfied.

Let  $k \geq 1$  and recall that  $B_{k}$  denotes the closed unit ball of  $\mathbb{R}^{k}$ . Let  $2 \leq r < \infty$  and let  $\widehat{\operatorname{End}_{k}^{r}} (M)$  be the set of  $C^{r}$ - families  $(f_{p})_{p \in B_{k}}$  of self- maps  $f_{p}$  of  $M$ .

THEOREM 1.9. Let  $\widehat{D}$  be a subset of families  $(f_{p})_{p \in B_{k}} \in \widehat{\operatorname{End}_{k}^{r}} (M)$  displaying a persistent  $r$ - normally hyperbolic fibration  $(\mathcal{L}_{p})_{p \in B_{k}}$  by circles with the following property:

$(\widehat{\mathcal{P}})$  The set  $B_{k}$  is covered by open subsets  $U_{i}$  associated with a  $q_{i}$ - periodic fiber  $\mathbb{T}_{y_{i},p}$  of  $\mathcal{L}$  at which the restriction  $f_{p}^{q_{i}}|_{\mathbb{T}_{y_{i},p}}$  is parabolic for every  $p \in U_{i}$ .

Then, for any  $(a_{n})_{n \in \mathbb{N}^{\mathbb{N}}}$ , a  $C^{r}$ - topologically generic  $(f_{p})_{p \in B_{k}}$  in the interior of  $\operatorname {cl}(\widehat{D})$  satisfies

$$
\lim_{n\to \infty}\sup_{a_n}\operatorname {Card}\operatorname {Per}_n^0 (f_p)\geqslant 1\quad for all p\in B_k.
$$

Proof of Theorem 1.9. Let  $(f_{p})_{p} \in \widehat{D}$ . By definition of persistence (see Theorem 1.6), for all  $i$ , the circle  $\mathbb{T}_{y_{i},p}$  depends continuously on  $p \in B_{k}$ . By compactness of  $B_{k}$ , we may assume that the covering  $(U_{i})_{i \in I}$  is finite. Up to merge the elements  $U_{i}$  of the covering associated with a same torus, we may assume the orbits of  $\mathbb{T}_{y_{i},p}$  and  $\mathbb{T}_{y_{j},p}$  are disjoint for  $i \neq j \in I$  and  $p \in U_{i} \cap U_{j}$ . By continuity, the distance between  $\mathbb{T}_{y_{i},p}$  and  $\mathbb{T}_{y_{j},p}$  is positive for  $i \neq j \in I$  and  $p \in B_{k}$ , and so it is uniformly bounded from below.

Let us show that we may assume that  $(f_{p}^{q_{i}}|_{\mathbb{T}_{y_{i},p}})_{p}$  is of class  $C^{\infty}$ . First note that the submanifold  $\bigcup_{p\in U_{i}}\{p\} \times \mathbb{T}_{y_{i},p}$  is  $r$ - normally hyperbolic for  $(p,z)\mapsto (p,f_{p}^{q_{i}}(z))$ . Thus, by [22, §Forced smoothness], the family  $(\mathbb{T}_{y_{i},p})_{p\in U_{i}}$  is of class  $C^{rr}$ . Therefore up to conjugate  $(f_{p})_{p}$  with a  $C^{rr}$ - family of conjugacy, we may assume that  $(\mathbb{T}_{y_{i},p})_{p\in U_{i}}$  is of class  $C^{\infty}$ . Let  $C_{i}(p)\in \mathbb{T}_{y_{i},p}$  be the parabolic periodic point and let us identify  $\mathbb{T}_{y_{i},p}$  with  $\mathbb{R} / \mathbb{Z}$ . Note that  $x\in \mathbb{T}_{y_{i},p}\mapsto f_{p}^{q_{i}}(x) - x$  is a unimodal map nearby  $C_{i}(p)$  and zero is its unique critical value. We now perform a smoothing of  $(f_{p})_{p}$  such that  $\mathbb{T}_{y_{i},p}$  remains  $q_{i}$ - periodic. Note that the induced perturbation of  $x\in \mathbb{T}_{y_{i},p}\mapsto f_{p}^{q_{i}}(x) - x$  is still unimodal nearby  $C_{i}(p)$ , but its critical value is in general different to zero. However, the critical values of a  $C^{rr}$ - family of unimodal maps depend  $C^{rr}$  on the parameter, and so the critical value of the smoothed map is a  $C^{rr}$ - small function of  $p$ . Thus, by composing with a local translation along this fiber, we can restore the critical value to zero. Then, we obtain a  $C^{rr}$ - perturbation of  $(f_{p})_{p}$  whose  $q_{i}$  iterate leaves invariant  $(\mathbb{T}_{y_{i},p})_{p\in U_{i}}$ , and its restriction at it is both parabolic and of class  $C^{\infty}$ . Thus, Theorem 1.4 implies the following.

FACT 1.10. There exists a  $C^{rr}$ - perturbation  $(\check{f}_{p})_{p\in B_{k}}$  of  $(f_{p})_{p\in B_{k}}$  such that, for all  $i$  and all  $p\in U_{i}$ , the map  $\check{f}_{p}^{q_{i}}$  is normally hyperbolic at  $\mathbb{T}_{y_{i},p}$ , the family of restrictions  $(\check{f}_{p}^{q_{i}}|_{\mathbb{T}_{y_{i},p}})_{p\in U_{i}}$  is of class  $C^{\infty}$ , and the rotation number of  $\check{f}_{p}^{q_{i}}|_{\mathbb{T}_{y_{i},p}}$  is a Diophantine number  $\alpha_{i}$  independent of  $p\in U_{i}$ .

Then, by the second part of Herman- Yoccoz' Theorem 1.1, the family  $\check{f}_{p}^{q_{i}}|_{\mathbb{T}_{y_{i},p}}$  is  $C^{\infty}$ - conjugated to the rotation  $R_{\alpha_{i}}$  for every  $p\in U_{i}$ , and the conjugacy  $h_{i_{\alpha}}$  depends infinitely smoothly on  $p$ . Hence, by the same reasoning as for the proof of Proposition 1.7, there exists an integer  $r_{i}\geq 1$  arbitrarily large and a  $C^{rr}$ - perturbation  $(\mathring{f}_{p})_{p}$  of  $(f_{p})_{p}$  such that, for every  $p\in U_{i}$ ,  $\mathring{f}_{p}^{q_{i}}$  leaves invariant  $\mathbb{T}_{y_{i},p}$  and

$$
\begin{array}{r}\mathring{f}_p^{q_i\cdot r_i}\big|_{\mathbb{T}_{y_i,p}} = \mathrm{id}_{\mathbb{T}_{y_i,p}}\mathrm{and}\mathring{f}_p^{q_i\cdot r}\big|_{\mathbb{T}_{y_i,p}}\neq \mathrm{id}_{\mathbb{T}_{y_i,p}}\mathrm{for~all}1\leqslant r< r_i. \end{array}
$$

Thus, for every  $i$ , there exists a non- trivial segment  $J_{ip}\in \mathbb{T}_{y_{i},p}$  depending smoothly on  $p$  and such that the family of segments  $(\mathring{f}_{p}^{k}(J_{ip}))_{0\leqslant k< q_{i}\cdot r_{i}}$  is disjoint for every  $p\in U_{i}$ .

Hence, we can perform a last perturbation  $(\mathring{f}_{p})_{p}$  of  $(\mathring{f}_{p})_{p}$  so that, for every  $p\in U_{i}$ , we have

$$
\tilde{f}_p^{r_i\cdot q_i}|_{J_{ip}:x\longmapsto x + \epsilon \rho_i(x)}\sin \left(\frac{2\pi\cdot a_{r_i\cdot q_i}\cdot x}{|J_{ip}|}\right)
$$

for an identification of  $\mathbb{T}_{y_{i},p}$  with  $\mathbb{R} / \mathbb{Z}$  such that the left endpoint of  $J_{ip}$  is zero and  $\epsilon >0$  is small.

Then, for all  $i$  and all  $p\in U_{i}$ , the map  $\tilde{f}_{p}$  displays at least  $a_{q_{i}\cdot r_{i}}$  saddle points of period  $r_{i}\cdot q_{i}$ . As these periodic points persist for small perturbations of  $\tilde{f}_{p}$ , this proves the existence of an open and dense set  $\widehat{\mathcal{M}}_N\subset \operatorname {int}(\operatorname {cl}\widehat{D})\eqqcolon \widehat{\mathcal{M}}$  such that, for every  $(\tilde{f}_{p})_{p}\in \widehat{\mathcal{M}}_{N}$  and every  $p\in B_{k}$ , the map  $\tilde{f}_{p}$  displays at least  $a_{r_{i}\cdot q_{i}}$  saddle points of period  $r_{i}\cdot q_{i}\geq N$ .

Note that the intersection  $\widehat{\mathcal{R}} \coloneqq \bigcap_{N \geqslant 0} \widehat{\mathcal{M}}_N$  is  $C^r$ - topologically generic in  $\widehat{\mathcal{M}}$  and for every  $(f_p)_p \in \widehat{\mathcal{R}}$ , for every  $p \in B_k$ , there exists  $n$  arbitrarily large such that

$$
\mathrm{Card}\mathrm{Per}_n^0 f_p\geqslant a_n.
$$

In the  $C^1$ - topology, we can perturb a neutral fixed point to make it locally equal to the identity. Thus, we can perform the same trick by adding a small oscillation of high frequency to obtain the following result.

COROLLARY 1.11. When  $r = 1$ , the conclusion of Theorem 1.9 holds true if we replace  $(\widehat{\mathcal{P}})$  by:

$(\widehat{\mathcal{P}}^{\prime})$  The set  $B_{k}$  is covered by open subsets  $U_{i}$  associated with a  $q_{i}$  - periodic fiber  $\mathbb{T}_{y_i,p}$  of  $L$  at which the restriction  $f_{p}^{q_{i}}|_{\mathbb{T}_{y_{i},p}}$  displays a parabolic fixed point varying continuously for every  $p\in U_{i}$

# 2. Locally dense properties of finitely generated groups of circle diffeomorphisms

The aim of this section is to develop and introduce notions and techniques which will be generalized to construct an open set of self- maps and families of self- maps satisfying the assumptions of Theorems 1.8 and 1.9. In particular, we will introduce two new objects, the  $\lambda$ - blender and the  $C^r$ -  $\lambda$ - parablender, which are developments of the Bonatti- Diaz blender [12] and the  $C^r$ - parablender introduced in [8] (see also [9]). To make these notions more apprehensive, we push forward some of the ingredients of [11] to develop the notions of blender and parablenders for IFS in §2.1, and introduce their  $\lambda$ - version diffeomorphisms with rotations in §2.2 and parabolic maps in §2.4.

# 2.1. Blender and parablender IFS

Let  $M$  be a manifold and let  $\operatorname {End}^r (M)$  be the space of self- maps of  $M$  of class  $C^r$  for every  $\infty \geqslant r \geqslant 0$  or  $r = \omega$ . Given a semi- group  $G \subset \operatorname {End}^0 (M)$ , a compact subset  $\Lambda$  is  $G$ - invariant if  $\Lambda = \bigcup_{g \in G} g(\Lambda)$ . It is transitive if it displays a dense  $G$ - orbit. The set  $\Lambda$  is a contracting attractor if  $G \subset \operatorname {End}^1 (M)$  and  $g|_{\Lambda}$  is contracting for every  $g \in G$ .

If there exists a finite set  $\mathcal{B}$  and  $(g^{\ell})_{\ell \in \mathcal{B}} \in \operatorname {End}^1 (M)^{\mathcal{B}}$  which generates  $G$ , then  $\Lambda$  is a contracting attractor for the iterated function system (IFS)  $(g^{\ell})_{\ell \in \mathcal{B}}$ . Given  $m \in \mathcal{B}^{(\mathbb{N})}$ , we denote  $|m| \in \mathbb{N}$  its number of letters in  $\mathcal{B}$ . The following is the IFS counterpart of the Bonatti- Diaz blender [12].

Definition 2.1. ( $C^{1}$ - Blender IFS) A contracting attractor  $\Lambda \subset M$  for an IFS

$$
(g^{\ell})_{\ell \in \mathcal{B}}\in \operatorname{End}^{1}(M)^{\mathcal{B}}
$$

is a blender if its interior is non- empty and for any subset  $K\Subset\Lambda$  , every  $C^1$  - perturbation of  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}}$  has a contracting attractor which contains  $K$

Example 2.2. Let  $\mathcal{B}_0\coloneqq \{- , + \}$  . The set  $\Lambda = [- 1,1]$  is a blender for the IFS  $(g^{\ell})_{\ell}$  with  $g^{- }:x\in \mathbb{R}\mapsto {\textstyle \frac{2}{3}}(x + 1) - 1\in \mathbb{R}$  and  $g^{+}\colon x\in \mathbb{R}\mapsto {\textstyle \frac{2}{3}}(x - 1) + 1\in \mathbb{R}$

Proof. For any  $\eta >0$  , the convex subset  $K\coloneqq [- 1 + \eta ,1 - \eta ]$  is sent by  $g^{- }$  and  $g^{+}$  onto  $\left[- 1 + \textstyle {\frac{2}{3}}\eta ,\textstyle {\frac{1}{3}} - \textstyle {\frac{2}{3}}\eta \right]$  and  $\left[- \textstyle {\frac{1}{3}} + \textstyle {\frac{2}{3}}\eta ,1 - \textstyle {\frac{2}{3}}\eta \right]$  , respectively. Thus, the following covering property holds true:

$$
K\subset \operatorname {int}g^{+}(K)\cup \operatorname {int}g^{-}(K).
$$

This property is stable for any  $C^1$  - perturbation  $(\tilde{g}^{+},\tilde{g}^{- })$  of  $(g^{+},g^{- })$  .Hence, for any perturbation of the dynamics, for any  $z_0\in K$  , there exists a preorbit  $(z_{i})_{i\leq 0}$  such that  $z_{i}$  belongs to  $K$  . By preorbit we mean that  $z_{i + 1} = g^{\alpha_i}(z_i)$  for a certain  $\alpha_{i}\in \mathcal{B}_{0}$  . Thus the continuation  $\tilde{\Lambda}$  of  $\Lambda$  contains  $K$  . The transitivity is left as an exercise to the reader.

For  $1\leq r< \infty$  , we now study semi- groups of parameter  $C^r$  - families  $(g_{p})_{p\in B_{k}}$  of selfmaps  $g_{p}\in \operatorname{End}^{r}(M)$  of a manifold  $M$  , parametrized by the closed unit  $k$  - ball  $B_{k}$  .We recall that  $\widehat{\operatorname{End}_k^r} (M)$  denotes the space of such families (which is itself a semi- group for the composition rule). As we will work with  $C^r$  - perturbations, we shall deal with the action of such families on  $C^r$  - jets. We recall that the  $C^r$  - jet at  $p_0\in B_k$  of a  $C^r$  - family of points  $z = (z_{p})_{p\in B_{k}}$  is

$$
J_{p_0}^r z = \sum_{j = 0}^r\frac{\partial_j^j z_{p_0}}{j!} (p - p_0)^{\otimes j}.
$$

Let  $J_{p_0}^r M$  be the space of  $C^r$  - jets at  $p_0$  of  $C^r$  - family  $z = (z_{p})_{p\in B_{k}}$  of points  $z_{p}\in M$  .We notice that any  $C^r$  - family  $g = (g_{p})_{p}\in \widehat{\operatorname{End}_{k}^{r}} (M)$  acts canonically on  $J_{p_0}^r M$  as

$$
J_{p_0}^r g\colon J_{p_0}^r (z_p)_p\in J_{p_0}^r M\longmapsto J_{p_0}^r (g_p(z_p))_p\in J_{p_0}^r M.
$$

Let  $\mathcal{B}$  be a finite set and, for every  $\ell \in \mathcal{B}$  , let  $g^{\ell} = (g_{p}^{\ell})_{p\in B_{k}}\in \widehat{\operatorname{End}_{k}^{r}} (M)$  . Let  $p_0\in B_k$  We recall that if  $\Lambda_{p_0}$  is a contracting attractor for the IFS  $(g_{p_0}^{\ell})_{\ell \in \mathcal{B}}$  . Then, for every point  $\Omega$  nearby  $\Lambda_{p_0}$  , the set  $\Lambda_{p_0}$  consists of the points  $X_{p_0}(\underline{\ell}) = \lim_{i\to \infty}g_{p_0}^{\ell_{- i}\ldots \ell_{- 1}}(\Omega)$  among  $\underline{\ell} = (\ell_{i})_{i< 0}\in \mathcal{B}^{\mathbb{Z}^{- }}$  . This limit does not depend on  $\Omega$  . Also, for every  $p$  nearby  $p_0$  the set of points  $X_{p}(\underline{\ell}) = \lim_{\infty}g_{p}^{\ell_{- i}\ldots \ell_{- 1}}(\Omega)$  among  $\underline{\ell}\in \mathcal{B}^{\mathbb{Z}^{- }}$  is a contracting attractor for  $(g_{p}^{\ell})_{\ell \in \mathcal{B}}$  . The family  $(\Lambda_{p})_{p}$  is called the continuation of  $\Lambda_{p_0}$  . Furthermore, the family

$(X_{p}(\underline{\ell}))_{p}$  is of class  $C^{r}$  for every  $\underline{\ell} \in \mathcal{B}^{\mathbb{Z}^{- }}$  and depends continuously on  $\underline{\ell}$ . We consider the subset

$$
J_{p_0}^r\Lambda \coloneqq \{J_{p_0}^r X(\underline{\ell}):\underline{\ell} \in \mathcal{B}^{\mathbb{Z}^-}\} \subset J_{p_0}^r M.
$$

This set is compact, invariant, and transitive for the IFS  $(J_{p_0}^r g^{\ell})_{\ell \in \mathcal{B}}$ . Roughly speaking, the continuation  $(\Lambda_p)_p$  is a  $C^r$ - parablender at  $p_0$  if  $J_{p_0}^r\Lambda$  is a blender for  $(J_{p_0}^r g^{\ell})_{\ell \in \mathcal{B}}$ . However, there is one tricky point: the maps  $J_{p_0}^r g^{\ell}$  are in general only continuous and not differentiable nor contracting at  $J_{p_0}^r\Lambda$ . However, these maps are topologically contracting.

PROPOSITION 2.3. There exists a neighborhood  $U$  of  $J_{p_0}^r\Lambda$  such that, for  $(\tilde{g}^{\ell})_{\ell}$ $C^r$ - close to  $(g^{\ell})_{\ell}$

(1) when the length of  $\mathcal{M}\in \mathcal{B}^{(\mathbb{N})}$  is large, the diameter of  $J^{r}\tilde{g}^{m}(U)$  approaches zero. 
(2) The families  $(J_{p_0}^r\widetilde{X}_p(\underline{\ell}))_{\underline{\ell}\in \mathcal{B}^{\mathbb{Z}^-}}$  and  $(J_{p_0}^r X_p(\underline{\ell}))_{\underline{\ell}\in \mathcal{B}^{\mathbb{Z}^-}}$  are uniformly close, when  $(\tilde{g}^{\ell})_{\ell}$  is  $C^r$ -close to  $(g^{\ell})_{\ell}$

Proof. First note that (1) implies (2). Let us show (1). At a neighborhood of  $\Lambda$ , the map  $\tilde{g}_p^m$  is a large composition of contractions when  $|m|$  is large. So,  $\partial_x\tilde{g}_p^m$  is small and even  $C^{r - 1}$ - small. Also, when  $|m|\to \infty$ , the derivative  $\partial_p^k\tilde{g}_p^m$  is a sum of compositions of an exponentially large number of maps which are almost all contractions. So,  $\partial_p^k\tilde{g}_p^m$  is close to a constant  $\ell_k$ . By the Faa- di- Bruno formula, there are polynomials  $B_{j,k}$  such that

$$
\begin{array}{l}{{\partial_{p}^{k}\tilde{g}_{p}^{m}(x_{p})=\sum_{j=0}^{k}\partial_{x}^{k}\partial_{p}^{j}g_{p}^{m}\cdot B_{j,k}\left(\partial_{p}x_{p},\partial_{p}^{2}x_{p},\ldots,\partial_{p}^{k-j}x_{p}\right)}}\\ {{\qquad=(\partial_{p}^{k}g_{p}^{m})(x_{p})+O(\|\partial_{x}\tilde{g}_{p}\|_{C^{k-1}}\|x_{p}\|_{C^{k}}).}}\end{array}
$$

Thus, at a neighborhood  $U$  of  $J_{p_0}^r\Lambda$ , when  $|m|$  is large, the map  $J_{p_0}^r g^m$  is close to the constant function

$$
\sum_{k = 0}^{r}\zeta_{k}\cdot (p - p_{0})^{k}\longmapsto \sum_{k = 0}^{r}\frac{\ell_{k}}{k!}\cdot (p - p_{0})^{k}.
$$

From this we obtain the following generalization of the covering property (compare to [11]).

PROPOSITION 2.4. The continuation  $(\Lambda_p)_p$  satisfies the  $J_{p_0}^r$ - covering property if the interior of  $J_{p_0}^r\Lambda$  is non- empty and there exists an increasing sequence of subsets

$$
K_{n}\Subset J_{p_{0}}^{r}\Lambda
$$

whose union is the interior of  $J_{p_0}^r\Lambda$  and such that

$$
\operatorname {cl}(K_n)\subset \bigcup_{\mathcal{B}}\operatorname {int}J_{p_0}^r g^{\ell}(K_n)\subset J_{p_0}^r\Lambda .
$$

Then, for any  $n \geq 0$  and any  $C^r$ - small perturbation  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}}$  of  $(g^{\ell})_{\ell \in \mathcal{B}}$ , the set  $J_{p_0}^r \tilde{\Lambda}$  contains  $K_n$ .

The following is the IFS counterpart of the  $C^r$ - parablender introduced in [8].

Definition 2.5. Given a  $C^r$  - family of IFS  $(g^{\ell})_{\ell \in \mathcal{B}}$  , the continuation  $(\Lambda_{p})_{p}$  of a blender  $\Lambda_{p_0}$  is a parablender at  $p_0$  if  $J_{p_0}^r\Lambda$  has non- empty interior and, for every  $K\Subset$ $J_{p_0}^r\Lambda$  , the continuation  $(\tilde{\Lambda}_{p})_{p}$  of a sufficiently small  $C^r$  - perturbation  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}}$  of  $(g^{\ell})_{\ell \in \mathcal{B}}$  satisfies  $J_{p_0}^r\tilde{\Lambda}\equiv K$

Given  $i = (i_1, \ldots , i_k) \in \mathbb{N}^k$  and  $p = (p_1, \ldots , p_k) \in \mathbb{R}^k$ , we work with the multi- index notation  $p^i \coloneqq p_1^{i_1} \ldots p_k^{i_k}$  and  $|i| = i_1 + \ldots + i_k$ . For  $r \in \mathbb{N}$ , let  $E_r \coloneqq \{e \in \mathbb{N}^k: |i| \leqslant r \}$ .

Example 2.6. Let  $\mathcal{B}_r \coloneqq \{- 1, 1\}^{E_r}$  and, for every  $\ell = (\ell_i)_{i \in E_r} \in \mathcal{B}_r$ , let

$$
P_{\ell}(p) = \sum_{i \in E_r} \ell_i \cdot p^i \quad \text{and} \quad g_p^{\ell} \coloneqq x \in \mathbb{R} \mapsto \frac{2}{3} (x - P_{\ell}(p)) + P_{\ell}(p).
$$

Then, the continuation of  $\Lambda_0 \coloneqq [- 1, 1]$  is a  $C^r$ - parablender at  $p = 0$  for  $((g_p^{\ell})_{p \in B_k})_{\ell \in \mathcal{B}_r}$ , with

$$
J_{0}^{r}\Lambda \coloneqq \left\{\sum_{i\in E_{r}}\xi_{i}\cdot p^{i}:(\xi_{i})_{i}\in [-1,1]^{E_{r}}\right\}
$$

Proof. First note that the set of diffeomorphisms  $\{g_0^{\ell} \in \mathcal{B}_r\}$  equals the one in Example 2.2 for which  $\Lambda_0 \coloneqq [- 1, 1]$  is a blender. Via the conjugacy  $(x_j)_{j \in E_r} \mapsto \sum_{E^r} x_j p^j$ , the set of maps  $(J_0^r g^{\ell})_{\ell \in \mathcal{B}_r}$  is conjugated to the Cartesian product of  $\text{Card} E_r$  times the set of maps in Example 2.2:

$$
\{J_0^r g^{\ell} \colon \ell \in \mathcal{B}_r\} \approx \{(x_j)_{j \in E_r} \mapsto (g^{\ell_j} (x_j))_{j \in E_r}: (\ell_i)_i \in \mathcal{B}^{E_r}\} \quad \text{using} \mathcal{B}_r \approx \mathcal{B}^{E_r}
$$

Thus,  $J_0^r \Lambda \approx [- 1, 1]^{E_r}$  is a product of blenders IFS satisfying the covering property and so the continuation  $(\Lambda_p)_p$  satisfies the assumptions of Proposition 2.4.  $\square$

# 2.2. Density of rotations from blender IFS

Let us explain how to use a blender to obtain the local density of semi- groups of finitely generated circle diffeomorphisms containing a rotation. We recall that the projectivized  $P^1 (\mathbb{R})$  of  $\mathbb{R}^2$  is a smooth circle which is canonically identified to the 1- point compactification  $\mathbb{R} \cup \{\infty \}$  of  $\mathbb{R}$  via the inclusion  $x \in \mathbb{R} \hookrightarrow [x; 1] \in P^1 (\mathbb{R})$ . This enables to extend analytically the dynamics of any non- zero real polynomial or even rational map of  $\mathbb{R}$  to this circle. These are the projectivized corresponding maps.

PROPOSITION 2.7. There exists a neighborhood  $N$  in  $\mathrm{Diff}^{1}(P^{1}(\mathbb{R}))$  of a triplet of homographies  $(g^{\alpha},g^{\beta},g^{\epsilon})$ , such that any  $(\tilde{g}^{\alpha},\tilde{g}^{\beta},\tilde{g}^{\epsilon})\in N\cap \mathrm{Diff}^{\infty}(P^{1}(\mathbb{R}))$  can be perturbed by conjugacies with homographies to span a semi- group containing a smooth, irrational rotation.

Proof. Let  $(g^{\alpha},g^{\beta})_{a,\ell \in \mathcal{B}_{0}}$  be the projectivized action of the affine maps of Example 2.2 and let  $V$  be a  $C^{1}$ - neighborhood of this pair of diffeomorphisms such that every  $(\tilde{g}^{\alpha},\tilde{g}^{\beta})\in V$  has a blender  $\bar{\Lambda}$  containing  $\left[- \frac{2}{3},\frac{2}{3}\right]$ . Let

$$
g^{\epsilon}\colon x\in P^{1}(\mathbb{R})\longmapsto \frac{3}{2}\frac{x}{x + 1}
$$

and let  $V^{\prime}$  be a small neighborhood of  $g^{\epsilon}$  formed by maps  $\tilde{g}^{\epsilon}$  which displays exactly two periodic points: an attracting  $x_{a}\approx \frac{1}{2}$  and a repulsive  $x_{r}\approx 0$ .

Let  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}_{0}}\in V$  and  $\tilde{g}^{\epsilon}\in V^{\prime}$  be of class  $C^{\infty}$ . Using the transitivity of the blender, there exists  $m\in \mathcal{B}_{0}^{(\mathbb{N})}$  such that  $\tilde{g}^{m}$  sends a point close to  $x_{a}$  to a point close to  $x_{r}$ . Hence, up to a small perturbation of  $\tilde{g}^{c}$  (using a composition with a homography), we may assume that  $\tilde{g}^{m}(x_{a}) = x_{r}$ . Now, we consider a small unfolding  $(\tilde{g}_{\epsilon}^{\epsilon})_{\epsilon \in [- \epsilon_{0},\epsilon_{0}]}$  of  $\tilde{g}^{\epsilon}\eqqcolon \tilde{g}_{0}^{\epsilon}$  such that, with  $x_{a}(\epsilon)$  and  $x_{r}(\epsilon)$  being the continuations of the fixed points  $x_{a}\eqqcolon x_{a}(0)$  and  $x_{r}\eqqcolon x_{r}(0)$ , respectively, we have

$$
x_{a}(-\epsilon_{0})< x_{a}< x_{a}(\epsilon_{0})\quad \mathrm{and}\quad x_{r}(\epsilon_{0})< x_{r}< x_{r}(-\epsilon_{0}).
$$

This can be done by conjugating the map  $\tilde{g}^{\epsilon}$  by  $\left(x\mapsto \left(1 + \epsilon\right)\left(x - \frac{1}{4}\right) + \frac{1}{4}\right)_{\epsilon}$ . Thus,  $x_{a}$  is sent to  $x_{r}$  by  $\tilde{g}^{m}$ . Then, for  $k$  large, the points  $((\tilde{g}_{\epsilon_{0}}^{\epsilon})^{j}(x_{r}))_{k\geqslant j\geqslant 0}$  go clockwise to land nearby  $x_{a}(\epsilon_{0}) > x_{a}$ .

$$
\tilde{g}^{m}(x_{a}) = x_{r}< \tilde{g}_{\epsilon_{0}}^{\epsilon}(x_{r})< \ldots < (\tilde{g}_{\epsilon_{0}}^{\epsilon})^{j}(x_{r})< \ldots < (\tilde{g}_{\epsilon_{0}}^{\epsilon})^{k}(x_{r}) > x_{a}.
$$

On the other hand, the points  $((\tilde{g}_{- \epsilon_{0}}^{\epsilon})^{j}(x_{r}))_{k\geqslant j\geqslant 0}$  go anti- clockwise to land nearby  $x_{a}(- \epsilon_{0})< x_{a}$ .

$$
\tilde{g}^{m}(x_{a}) = x_{r} > \tilde{g}_{-\epsilon_{0}}^{\epsilon}(x_{r}) > \ldots >(\tilde{g}_{-\epsilon_{0}}^{\epsilon})^{j}(x_{r}) > \ldots >(\tilde{g}_{-\epsilon_{0}}^{\epsilon})^{k}(x_{r})< x_{a}.
$$

Thus, when  $\epsilon$  varies between  $- \epsilon_{0}$  and  $\epsilon_{0}$ , the point  $(\tilde{g}_{\epsilon}^{\epsilon})^{k}\circ \tilde{g}^{m}(x_{a})$  makes at least one whole turn around  $P^{1}(\mathbb{R})$ . This implies that the rotation number of  $(\tilde{g}_{\epsilon}^{\epsilon})^{k}\circ \tilde{g}^{m}$  is not constant when  $\epsilon$  varies in  $[- \epsilon_{0},\epsilon_{0}]$ . Thus, by continuity of the rotation number and density of the Diophantine ones, there exists  $\epsilon \in (- \epsilon_{0},\epsilon_{0})$  such that the rotation number of  $\tilde{g}_{\epsilon}^{\epsilon^{n}}\circ \tilde{g}^{m}$  is Diophantine. By Arnold- Herman- Yoccoz Theorem 1.1, the map  $\tilde{g}_{\epsilon}^{\epsilon^{n}}\circ \tilde{g}^{m}$  is smoothly conjugate to the rotation  $R_{\alpha}$ .

This proposition implies the first part of Corollary A. However, the technique is not easy to generalize to obtain a parametric version of this result. We know that the set  $D$  of Diophantine smooth rotations is an union of 1- codimensional submanifolds, and these appear locally  $C^0$ - densely from the above argument. However, this does not provide any control on the tangent spaces of these manifolds, while it is crucial for Theorem B. To obtain such a control, we will focus on parabolic maps and introduce the  $\lambda$ - blender to show their density.

# 2.3.  $\lambda$ -blender and  $\lambda$ -parablender IFS

Let  $M$  be  $\mathbb{R}$  or  $P^1 (\mathbb{R}) \approx \mathbb{R} / \mathbb{Z}$ ; its tangent bundle is identified with  $M \times \mathbb{R}$ .

Definition 2.8. The Lyapunov fibration of a contracting attractor  $\Lambda$  for an IFS  $(g^{\ell})_{\ell \in \mathcal{B}}$  of  $M$  is

$$
\lambda (\Lambda)\coloneqq \bigcap_{n\geqslant 0}\operatorname {cl}\left\{\left(g^{m}(x),\frac{1}{|m|}\log |D_{x}g^{m}|\right):x\in \Lambda ,m\in \mathcal{B}^{(\mathbb{N})}\mathrm{~and~}|\mathcal{m}|\geqslant n\right\} \subset \Lambda \times \mathbb{R}
$$

To show the local density of finitely generated group of circle diffeomorphisms with a parabolic element, we introduce the following new notion.

Definition 2.9. (  $\lambda$  - Blender IFS) A blender  $\Lambda$  for an IFS  $(g^{\ell})_{\ell \in \mathcal{B}}\in \mathrm{End}^{1}(M)^{\mathcal{B}}$  is a  $\lambda$  - blender if its Lyapunov fibration  $\lambda (\Lambda)$  has non- empty interior, and for any subset  $K\Subset\lambda(\Lambda)$  , for every  $C^1$  - small perturbation of  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}}$  , the Lyapunov fibration of the continuation of  $\Lambda$  contains  $K$

Example 2.10. Let  $\mathcal{B}_0^\lambda \coloneqq \{- 1, + 1\} ^2$  . Then, for  $\epsilon >0$  small,  $[- 1,1]$  is a  $\lambda$  - blender for the IFS  $(g^{\ell})_{\ell \in \mathcal{B}_0^\lambda}$  , where  $\begin{array}{r}g^{\ell}:x\in \mathbb{R}\mapsto \frac{2}{3}\cdot \exp (\epsilon \cdot \delta^{\prime})\cdot (x + \delta) - \delta \end{array}$  for  $\ell = (\delta ,\delta^{\prime})\in \mathcal{B}_{0}^{\lambda}$  and with Lyapunov fibration

$$
\lambda (\Lambda)\coloneqq [-1,1]\times \left[\log \frac{2}{3} -\epsilon ,\log \frac{2}{3} +\epsilon \right]\subset \mathbb{R}\times \mathbb{R}.
$$

Proof. Let  $\eta > 0$  be small and let

$$
K\coloneqq [-1 + \eta ,1 - \eta ]\times \bigl [\log \frac{2}{3} -\epsilon +\eta ,\log \frac{2}{3} +\epsilon -\eta \bigr ].
$$

Let  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}}$  be a  $C^1$  - perturbation of  $(g^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}}$  . It suffices to show, for every  $(x_{0},\ell)\in K$  and  $n\geqslant 0$  , the existence of a sequence of letters  $(\ell_{i})_{- n\leqslant i< 0}\in (\mathcal{B}_{0}^{\lambda})^{n}$  and a sequence of points  $(x_{i})_{- n\leqslant i< 0}\in [- 1 + \eta ,1 - \eta ]^{n}$  such that

(1)  $x_0 = x$  and  $\tilde{g}^{\ell_i}(x_i) = x_{i + 1}$  for every  $-n \leqslant i < 0$ ,  
(2)  $-2\epsilon \leqslant \log |D_{x_{-n}}g^{\ell_{-n} \dots \ell_{-1}}| - n \cdot \ell \leqslant 2\epsilon$ .

The step  $n = 0$  is trivial. Assume the result shown for  $n\geq 0$  . Then, with  $\delta$  the sign of  $x_{- n}$  and  $\delta^{\prime}$  the sign of  $- (\log |D_{x - n}\tilde{g}^{\ell - n\dots \ell - 1}| - n\ell)$  , with  $\ell = (\delta ,\delta^{\prime})\in \{- 1,1\}^{2} = \mathcal{B}_{0}^{\lambda}$  and with  $x_{- n - 1}$  the preimage by  $\tilde{g}^{\ell - n - 1}$  of  $x_{- n}$  , the induction hypothesis holds true by the covering property showed in Example 2.2. Indeed, if  $\delta^{\prime} = +1$  then

$$
\log |D_{x_{-n}}\tilde{g}^{\ell -n\dots \ell -1}| - n\ell \leqslant 0
$$

and  $\log |D_{x_{- n - 1}}\tilde{g}^{\ell - n - 1}| - \ell$  is approximately in

$$
\log \frac{2}{3} +\epsilon -\left[\log \frac{2}{3} -\epsilon +\eta ,\log \frac{2}{3} +\epsilon -\eta \right] = [\eta ,2\epsilon -\eta ].
$$

Thus,

$$
0\geqslant \log |D_{x_{-n}}\tilde{g}^{\ell_{-n}\dots \ell_{0}^{\ell}}| - n\ell > - 2\epsilon \quad \mathrm{and}\quad 2\epsilon >\log |D_{x_{-n - 1}}\tilde{g}^{\ell_{-n - 1}}| - \ell >0.
$$

Summing these two bounds, we obtain (2). The case  $\delta^{\prime} = - 1$  is done similarly.

Let us now give the parametric counterpart of the  $\lambda$  - blender. Let  $M$  be a curve; its tangent bundle is identified with  $M\times \mathbb{R}$  . Let  $\mathcal{B}$  be a finite set and for every  $\ell \in \mathcal{B}$  , let  $g^{\ell} = (g_{p}^{\ell})_{p\in B_{k}}\in \widehat{\mathrm{End}_{k}^{*}} (M)$  . Let  $p_0\in B_k$  . We recall that, if  $\Lambda_{p_0}$  is a contracting attractor for the IFS  $(g_{p_0}^{\ell})_{\ell \in \mathcal{B}}$  , then for every point  $\Omega$  nearby  $\Lambda_{p_0}$  and  $p$  nearby  $p_0$  , the set

$$
\mathfrak{p}\coloneqq \{\lim_{\infty}g_{p}^{\ell_{-i}\ldots \ell_{-1}}(\Omega):\underline{\ell}\in \mathcal{B}^{\mathbb{Z}^{-}}\} = \bigcap_{n\geqslant 0}\mathrm{cl}\big(\{g_{p}^{m}(\Omega):m\in \mathcal{B}^{(\mathbb{N})}\mathrm{~and~}|m|\geqslant \mathcal{B}^{(\mathbb{N})}\} \big).
$$

is the continuation of  $\Lambda_{p_0}$  . It does not depend on  $\Omega$  . Its Lyapunov fiber is

$$
\lambda (\Lambda_{p}) = \bigcap_{n\geqslant 0}\operatorname {cl}\biggl \{\Bigl (g_{p}^{m}(\Omega),\frac{1}{|m|}\log |D_{\Omega}g_{p}^{m}|\Bigr):m\in \mathcal{B}^{(\mathbb{N})}\mathrm{~and~}|m|\geqslant n\biggr \} .
$$

While studying the  $C^T$  - parablender, we considered

$$
\mathfrak{p}_{0}^{r}\Lambda \coloneqq \{J_{p_{0}}^{r}\lim_{\infty}g_{p}^{\ell_{-i}\ldots \ell_{-1}}(\Omega):\underline{\ell}\in \mathcal{B}^{\mathbb{Z}^{-}}\} = \bigcap_{n\geqslant 0}\operatorname {cl}\{J_{p_{0}}^{r}g_{p}^{m}(\Omega):m\in \mathcal{B}^{(\mathbb{N})}\mathrm{~and~}|m|\geqslant \mathcal{B}^{(\mathbb{N})}\} \} .
$$

It is thus natural to consider the following para- counterpart the Lyapunov fiber:

$$
\mathfrak{p}_{0}^{r}\Lambda)\coloneqq \bigcap_{n\geqslant 0}\operatorname {cl}\biggl \{\Bigl (J_{p_{0}}^{r}g_{p}^{m}(\Omega),J_{p_{0}}^{r - 1}\frac{1}{|m|}\log |D_{\Omega}g_{p}^{m}|\Bigr):m\in \mathcal{B}^{(\mathbb{N})}\mathrm{~and~}|m|\geqslant \mathcal{B}^{(\mathbb{N})}\biggr \} .
$$

We notice that  $\lambda (J_{p_0}^r\Lambda)$  is a compact subset of  $J_{p_0}^r M\times J_{p_0}^{r - 1}\mathbb{R}$

The following is a natural generalization of both the  $C^T$  - parablender and the  $\lambda$  blender. This new notion can be used to prove the local density of finitely generated groups of families of circle diffeomorphisms with a parabolic element at every parameter.

Definition 2.11.  $(C^{r} - \lambda$  - parablender IFS) The family  $(\Lambda_{p})_{p}$  of contracting attractors for  $(g^{\ell})_{\ell \in \mathcal{B}}$  is a  $C^{r} - \lambda$  - parablender at  $p_0$  if  $\lambda (J_{p_0}^r\Lambda)$  has non- empty interior and for any subset  $K\Subset\lambda(J_{p_0}^r\Lambda)$  , the continuation  $(\tilde{\Lambda}_{p})_{p}$  of every  $C^{r}$  - perturbation  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}}$  of  $(g^{\ell})_{\ell \in \mathcal{B}}$  satisfies  $\lambda (J_{p_0}^r\tilde{\Lambda})\equiv K$

Remark 2.12. We notice that  $\Lambda_{p_0}$  is a  $\lambda$  - blender for  $(g^{\ell_{p_0}})_{\ell}$  and  $(\Lambda_{p})_{p}$  is a  $C^{r}$  parablender at  $p = p_{0}$  for  $(g^{\ell})_{\ell}$

Example 2.13. Let  $\mathcal{B}_r$  and  $(P_{\ell})_{\ell \in \mathcal{B}_r}$  be defined as in Example 2.6 and put

$$
\mathcal{B}_r^\lambda \coloneqq \mathcal{B}_r\times \mathcal{B}_{r - 1}.
$$

Then, for  $\epsilon >0$  small, the continuation of  $\Lambda \coloneqq [- 1,1]$  is a  $C^{r} - \lambda$  - parablender at  $p = 0$  for  $(g^{\ell})_{\ell \in \mathcal{B}_{r}^{\lambda}}$  , where  $g^{\ell} = (g^{\ell_{p}})_{p\in B_{k}}$  is defined by

$$
\begin{array}{r}{\mathcal{G}_{p}^{\ell}:x\in P^{1}(\mathbb{R})\longmapsto \frac{2}{3}\cdot \exp (\epsilon \cdot P_{\ell^{\prime}}(p))\cdot (x - P_{\ell^{\prime}}(p)) + P_{\ell^{\prime}}(p)\quad \mathrm{for~}(\ell^{\prime},\ell^{\prime})\in \mathcal{B}_{r}\times \mathcal{B}_{r - 1} = \mathcal{B}_{r}^{\lambda}.} \end{array}
$$

Moreover, we have

$$
\lambda (J_{0}^{r}\Lambda) = \Bigg\{\Bigg(\sum_{i\in E_{r}}\xi_{i}\cdot p^{i},\log \frac{2}{3} +\epsilon \sum_{i\in E_{r - 1}}\lambda_{i}\cdot p^{i}\Bigg):(\xi_{i})_{i}\in [-1,1]^{E_{r}},(\lambda_{i})_{i}\in [-1,1]^{E_{r - 1}}\Bigg\} \Bigg\} .
$$

Proof. Let  $\eta >0$  be small and put  $I\coloneqq [- 1 + \eta ,1 - \eta ]\Subset [- 1,1]$  and:

$$
K\coloneqq \Bigg\{\Bigg(\sum_{i\in E_r}\xi_i\cdot p^i,\log \frac{2}{3} +\epsilon \sum_{i\in E_{r - 1}}\lambda_i\cdot p^i\Bigg):(\xi_i)_i\in I^{E_r},(\lambda_i)_i\in I^{E_{r - 1}}\Bigg\} .
$$

Let  $(\tilde{g}^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}}$  be a  $C^{r}$  - perturbation of  $(g^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}}$  . It suffices to show that for every  $(x_0,\ell)\in K$  and  $n\geqslant 0$  , the existence of a sequence of letters  $(\ell_{j})_{- n\leqslant j< 0}\in (\mathcal{B}_{0}^{\lambda})^{n}$  and a sequence of points  $(x_{j},\ell_{j})_{- n\leqslant j< 0}\in K^{n}$  such that

(1)  $J_{p_0}^r\tilde{g}^{\ell_j}(x_j) = x_{j + 1}$  for every  $-n\leq j< 0$  
(2)  $\begin{array}{r}\ell_{n} = J_{p_{0}}^{r - 1}(\log |D_{x_{-n}(p)}\tilde{g}_{p}^{\ell_{-n}\dots \ell_{-1}}|)_{p}\in \{n\ell +\sum_{i\in E_{r - 1}}\lambda_{i}\cdot p^{i}:\lambda_{i}\in [-2\epsilon ,2\epsilon ]\} . \end{array}$

The step  $n = 0$  is obvious. Assume the result shown for  $n\geqslant 0$  . Let  $\ell_{- n - 1}\in \mathcal{B}_r^\lambda$  be the upplet whose coefficients are the sign of those of the polynomial

$$
(x_{-n}, - \log |D_{x_{-n}}g^{\ell_{-n}\dots \ell_{-1}}| + n\ell).
$$

Then, for the same reasons as for Examples 2.6 and 2.10 the induction hypothesis holds true at step  $n + 1$

# 2.4. Density of parabolic maps from  $\lambda$ -blender IFS

We now introduce a technique based on a dynamical rescaling. It enables to show that a group contains a parabolic map nearby a prescribed one, say

$$
h\colon x\in P^{1}(\mathbb{R})\longmapsto \frac{x}{2x + 1}\in P^{1}(\mathbb{R}),
$$

and this for a dense set of perturbations of its generator. This method involves the  $\lambda$ - parablender of 2.10 extended to the projective space  $P^{1}(\mathbb{R})$  and the map  $g^{\ell}$  which is conjugate to  $\Delta \colon x\mapsto {\frac{3}{2}}x$  via the parabolic map  $h$ :

$$
g^{\ell} = h\circ \Delta \circ h^{-1}\colon x\in P^{1}(\mathbb{R})\longmapsto \frac{3}{2}\frac{x}{x + 1}\in P^{1}(\mathbb{R}). \tag{2.1}
$$

The map  $g^{\ell}$  has an expanding fixed point at  $x_{r} = 0$  with eigenvalue  $\frac{3}{2}$ . Given a perturbation  $\tilde{g}^{\ell}$  of  $g^{\ell}$ , we denote  $\tilde{x}_{r}$  the continuation of  $x_{r}$ . Let  $\tilde{g}^{\ell^{n}}$  be the composition of  $n$ - times  $\tilde{g}^{\ell}$ . The proof of the following contains the aforementioned key technique. It will be generalized to prove the main theorems, and should be fruitful to generalize to an even broader setting.

PROPOSITION 2.14. For every  $r\geq 2$ , for every  $n\geqslant 1$  large and  $C^{r}$ - perturbation

$$
(\tilde{g}^{\ell},(\tilde{g}^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}})
$$

of  $(g^{\ell},(g^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}})$ , for every  $\ell_{n}\in (\mathcal{B}_{0}^{\lambda})^{n}$  if

$$
\tilde{g}^{\ell_{n}}(\tilde{x}_{r}) = \tilde{x}_{r} = \tilde{g}^{\ell}(\tilde{x}_{r})\quad \text{and}\quad \frac{1}{n}\log |D_{\tilde{x}_{r}}\tilde{g}^{\ell_{n}}| = -\log |D_{\tilde{x}_{r}}\tilde{g}^{\ell}|,
$$

then the map  $\breve{h} \coloneqq \breve{g}^{\ell^{n}}\circ \tilde{g}^{\ell_{n}}$  is parabolic and its restriction to  $\left[- \frac{3}{2},\frac{3}{2}\right]$  is  $C^{r}$ - close

$$
h|_{[-3 / 2,3 / 2]}.
$$

As  $\left(0,\log {\frac{3}{2}}\right)$  belongs to the Lyapunov fibration of the  $\lambda$ - blender defined by  $(g^{\ell})_{\mathcal{B}_{0}^{\lambda}}$  for  $(\tilde{g}^{\ell},(\tilde{g}^{\ell})_{\mathcal{B}_{0}^{\lambda}})$  in a  $C^{r}$ - neighborhood of  $(g^{\ell},(g^{\ell})_{\mathcal{B}_{0}^{\lambda}})$ , when  $n$  is large, there is  $\ell_{n}\in (\mathcal{B}_{0}^{\lambda})^{n}$  such that  $\tilde{g}^{\ell_{n}}$  displays a fixed point close to  $\tilde{x}_{r}$ , with Lyapunov exponent close to  $\log |D_{\tilde{x}_{r}}\tilde{g}^{\ell}|$ . Thus, there is a perturbation of  $\tilde{g}^{\ell}$  of the form  $(1 + \epsilon^{\prime})\cdot \tilde{g}^{\ell} + \epsilon$  satisfying the assumptions of the above proposition. This shows the following.

COROLLARY 2.15. For every  $C^{2}$ - perturbation  $(\tilde{g}^{\ell},(\tilde{g}^{\ell})_{\mathcal{B}_{0}^{\lambda}})$  of  $(g^{\ell},(g^{\ell})_{\mathcal{B}_{0}^{\lambda}})$ , there exist  $\epsilon ,\epsilon^{\prime}\in \mathbb{R}$  arbitrarily small such that the semi- group spanned by  $(\exp (\epsilon^{\prime})\cdot \tilde{g}^{\ell} + \epsilon ,(\tilde{g}^{\ell})_{\mathcal{B}_{0}^{\lambda}})$  contains a parabolic diffeomorphism.

Proof of Proposition 2.14. First note that, if  $\breve{h} \in \mathrm{Diff}^2 (P^1 (\mathbb{R}))$  has its restriction to  $\left[- \frac{3}{2}, \frac{3}{2}\right]$  which is  $C^2$ - close to  $h$  and has a parabolic point nearby zero, then  $\breve{h}$  cannot have another fixed point in  $\left[- \frac{3}{2}, \frac{3}{2}\right]$ , indeed the parabolic fixed point of  $h(x) = x / (2x + 1)$  is non- degenerate. It cannot have another fixed point in  $P^1 (\mathbb{R}) \setminus \left[- \frac{3}{2}, \frac{3}{2}\right]$  since  $h$  sends  $P^1 (\mathbb{R}) \setminus \left[- \frac{3}{2}, \frac{3}{2}\right]$  onto  $\left[\frac{3}{8}, \frac{3}{4}\right] \in \left(- \frac{3}{2}, \frac{3}{2}\right)$ , and so the same holds true for  $\breve{h}$ . As  $\breve{h}$  has by assumption a parabolic point nearby zero, to show the proposition, it suffices to prove the following claim.

CLAIM 2.16. Under the assumptions of Proposition 2.14, the restriction of the map  $\breve{h} \coloneqq \tilde{g}^{\ell^n} \circ \tilde{g}^{\ell^n}$  to  $\left[- \frac{3}{2}, \frac{3}{2}\right]$  is  $C^r$ - close to  $h|_{[- 3 / 2, 3 / 2]}$ .

Up to a coordinate change close to the identity, we may assume that the fixed point  $\tilde{x}_r$  of  $\tilde{g}^e$  is equal to zero. Then, in these coordinates, we shall prove that  $\breve{h} |_{[- 5 / 3, 5 / 3]}$  is  $C^r$ - close to the identity.

THEOREM 2.17. (Sternberg [36]) There exists a map  $\breve{h}$  which is  $C^r$ - close to  $h$ , for which zero is a parabolic fixed point and such that  $\tilde{h} |_{[- 2, 2]} = \tilde{g}^{\ell^n} \circ \tilde{h} \circ (D_0 \tilde{g}^{\ell^n})^{- 1} |_{[- 2, 2]}$ .

Proof. Let  $B$  be the subset of  $C^r ([- 2, 2], \mathbb{R})$  formed by maps  $\bar{h}$  such that  $\bar{h} (0) = 0$  and  $D_0 \bar{h} = 1$ , is complete for the distance

$$
d(h, h) = \max_{2 \leqslant k \leqslant r} \| D^k h - D^k h\|_{\infty}.
$$

The operator

$$
\bar{h} \in B \longmapsto \tilde{g}^{\ell} \circ \bar{h} \circ (D_0 \tilde{g}^{\ell})^{-1}
$$

depends continuously on  $\tilde{g}^e$  and has a contracting iterate. Its fixed point  $\tilde{h} \in C^r ([- 2, 2], \mathbb{R})$  depends continuously on  $\tilde{g}^e$  and satisfies

$$
\tilde{h} |_{[-2, 2]} = \tilde{g} \circ \tilde{h} \circ (D_0 \tilde{g}^{\ell})^{-1} |_{[-2, 2]}.
$$

As when  $\tilde{g}^e = g^e$  the fixed point is  $h$  by (2.1), when  $\tilde{g}^e$  is close to  $g^e$  the fixed point  $\tilde{h} \in B$  is  $C^r$ - close to  $h$ .

Then, the dynamical rescaling techniques consist of noting that  $\breve{h} = \tilde{h} \circ \Phi$ , where  $\tilde{h}$  was bounded by the above theorem and

$$
\Phi = D_0 \tilde{g}^{\ell^n} \circ \tilde{h}^{-1} \circ \tilde{g}^{\ell^n} |_{[-2, 2]}
$$

is bounded by the following.

LEMMA 2.18. The map  $\Phi = D_0 \tilde{g}^{\ell^n} \circ \tilde{h}^{- 1} \circ \tilde{g}^{\ell^n} |_{[- 2, 2]}$  is  $C^r$ - close to the identity.

This lemma implies that  $\Phi \left(\left[- \frac{5}{3},\frac{5}{3}\right]\right)$  is included in  $[- 2,2]$ , and so the composition  $\tilde{h}\circ \Phi$  is well defined on  $\left[- \frac{5}{3},\frac{5}{3}\right]$ , equal to  $\tilde{h}$ , and is  $C^r$ - close to  $\tilde{h}$  and so  $h$ . This proves the claim.  $\square$

Proof of Lemma 2.18. By assumption of Proposition 2.14,  $\tilde{x}_r = 0$  is a neutral fixed point of  $\Phi$  which is equal to  $(D_0\tilde{g}^{\ell_n})^{- 1}\circ \tilde{h}^{- 1}\circ \tilde{g}^{\ell_n}|_{[- 2,2]}$ . Thus, it suffices to show that  $D^2\Phi$  is  $C^{r - 2}$ - small:

$D^{2}\Phi = (D_{0}\tilde{g}^{\ell_{n}})^{- 1}\cdot D^{2}\tilde{h}^{- 1}\cdot (D\tilde{g}^{\ell_{n}})^{2} + \sum_{i = 1}^{n}D_{0}\tilde{g}^{\ell_{n}}\cdot D\tilde{h}^{- 1}\cdot D\tilde{g}^{\ell_{n}^{n,i + 1}}\cdot D^{2}\tilde{g}^{\ell_{n}^{i}}\cdot (D\tilde{g}^{\ell_{n}^{i}})$ $\cdot (D\tilde{g}^{\ell_{n}^{i - 1,1}})^{2}$  where  $\tilde{g}^{\ell_{n}^{n,i + 1}}\coloneqq \tilde{g}^{\ell_{n}^{n}}\circ \dots \circ \tilde{g}^{\ell_{n}^{i + 1}}$  and  $\tilde{g}^{\ell_{n}^{i - 1,1}}\coloneqq \tilde{g}^{\ell_{n}^{i - 1}}\circ \dots \circ \tilde{g}^{\ell_{n}^{1}}$ , with  $\ell_{n}\coloneqq \ell_{n}^{n}\dots \ell_{n}^{i}\dots \ell_{n}^{1}$ . The first term  $(D_0\tilde{g}^{\ell_n})^{- 1}\cdot D^2\tilde{h}^{- 1}\cdot (D\tilde{g}^{\ell_n})^2$  is of the order of  $|D\tilde{g}^{\ell_n}\|$  which is small. The sum is small since the derivatives  $D^2\tilde{g}^{\ell_n}$  are all small, whereas

$$
|(D_0\tilde{g}^{\ell_n})^{-1}\cdot D\tilde{h}^{-1}\cdot D\tilde{g}^{\ell_n^{n,i + 1}}|\cdot |(D\tilde{g}^{\ell_n^{i - 1,1}})^2 |
$$

is of the order of  $|D\tilde{g}^{\ell_n^{i - 1,1}}|$ , which is exponentially  $C^{r - 1}$ - small when  $n - i$  is large.  $\square$

# 3. Intrinsic definition of  $(\lambda)$ -( $\text{para}$ )-blenders

In this section we are going to embed the  $\lambda$  and/or parablender IFS into normally hyperbolic fibrations for a single differentiable dynamics of a manifold. The attractors of these IFS will persist as hyperbolic basic sets. We are going to introduce a formalism to study their intrinsic properties. These will be used in the next section via a generalization of Corollary 2.15 together with Theorems 1.8 and 1.9 to prove Theorems A and B.

# 3.1. Embedding a semi-group into a normally hyperbolic fibration

Let  $1\leqslant r\leqslant \infty$ . Let  $\mathcal{A}$  be a finite alphabet and let  $\Sigma = \mathcal{A}^{\mathbb{I}}$  with  $\mathbb{I} = \mathbb{N}$  or  $\mathbb{Z}$ . This is a compact space endowed with the product topology. Its shift dynamics is denoted by  $\sigma \colon \mathcal{I} = (a_i)_i\in \Sigma \mapsto (a_{i + 1})_i\in \Sigma$ . Let  $N$  be a compact manifold. The aim of this subsection is to recall that the orbit of a finitely generated semi- group can be 'persistently' embedded into the following class of maps.

Definition 3.1. A  $C^r$ - endomorphism of  $\Sigma \times N$  over  $\sigma$  is a self- map of  $\Sigma \times N$  of the form

$$
g\colon (\mathcal{s},x)\in \Sigma \times N\longmapsto (\sigma (\mathcal{s}),g^{\mathcal{I}}(x)),
$$

where  $(g^{\mathcal{I}})_{\mathcal{I}\in \Sigma}$  is a continuous family of  $C^r$ - maps of  $N$ . The space of  $C^r$ - endomorphisms over  $\sigma$  is denoted by  $\operatorname {End}_{\sigma}^{r}(\Sigma \times N)$ . Two  $C^r$ - endomorphisms  $g,\tilde{g}\in \operatorname {End}_{\sigma}^{r}(\Sigma \times N)$  are close if their induced families  $(g^{\mathcal{I}})_{\mathcal{I}\in \Sigma}$  and  $(\tilde{g}^{\mathcal{I}})_{\mathcal{I}\in \Sigma}$  are uniformly close for the  $C^r$ - topology.

Example 3.2. (Canonical map of  $\operatorname{End}_{\sigma}^{r}(N)$  associated with  $(g^{a})_{a\in \mathcal{A}}$ ) A family

$$
(g^{a})_{a\in \mathcal{A}}
$$

of  $C^{r}$ - maps of  $N$  is canonically associated with the following endomorphism of  $\Sigma \times N$ :

$g\colon (\iota ,x)\longmapsto (\sigma (\iota),g^{\iota}(x))$  ,where  $g^{\mathcal{I}} = g^{\mathcal{U}}$  if  $a\in \mathcal{A}$  is the letter of  $\mathcal{J}$  at the 0- position.

For every  $m\in \mathcal{A}^{(\mathbb{N})}$  , the element  $g^{m}$  of the semi- group spanned by  $(g^{a})_{a\in \mathcal{A}}$  is equal to the restriction of  $g^{|m|}$  to the  $|m|$  - periodic fiber  $\{m^{\infty}\} \times N$  , with  $m^{\infty}\in \Sigma$  the  $|m|$  - periodic point whose  $\mathcal{A}$  - letters at the  $0,1,\dots,|\mathcal{m}| - 1$  positions are those of  $m$  . Hence, any element of the semi- group is equal to the dynamics of a periodic fiber. Now we would like to embed this dynamics into the one of a manifold  $M$  . This requires the following notion.

Definition 3.3. A  $C^{r}$ - embedding of  $\Sigma \times N$  into  $M$  is a map of the form

$$
j\colon (\iota ,x)\in \Sigma \times N\longmapsto j^{\iota}(x)\in M,
$$

where  $(j^{\mathcal{I}})_{\mathcal{I}\in \Sigma}$  is a continuous family of  $C^{r}$  - embedding of  $N$  into  $M$  with disjoint images. Two  $C^{r}$  - embeddings are  $C^{r}$  - close if their families of  $C^{r}$  - maps are uniformly  $C^{r}$  - close. The space of  $C^{r}$  - embeddings of  $\Sigma \times N$  into  $M$  is denoted by  $\operatorname{Emb}^{r}(\Sigma \times N,M)$

Let  $f$  be a  $C^{r}$  - self- map of  $M$  which leaves invariant a fibration  $\textstyle {\mathcal{L}} = \bigcup_{j\in \Sigma}L_{j}$  , where  $L_{\mathcal{J}}\coloneqq j^{\mathcal{J}}(N)$  is defined by  $j\in \operatorname{Emb}^{r}(\Sigma \times N,M)$  . We assume that the dynamics between the fibers is given by the shift  $\sigma$  : for every  $\mathcal{J}\in \Sigma$  , the fiber  $L_{\mathcal{J}}$  is sent by  $f$  into the fiber  $L_{\sigma (\mathcal{J})}$  Then,  $g\coloneqq j^{- 1}\circ f\circ j$  is a  $C^{r}$  - endomorphisms of  $\Sigma \times N$  over  $\sigma$  . Let us restate Theorem 1.6 in this terminology.

THEOREM 3.4. Assume that  $f$  is  $r$  - normally hyperbolic at  $L$  . Moreover, if  $f$  is not a diffeomorphism, we assume that  $f$  is  $r$  - normally expanding at  $L$  . Then, for every  $\tilde{f} C^{r}$  close to  $f$  there exists an embedding  $\tilde{j}\in \operatorname{Emb}^{r}(\Sigma \times N,M)$  close to  $j$  and  $\tilde{g}\in \operatorname{End}_{\sigma}^{r}(\Sigma \times N)$  close to  $g$  such that

$$
\tilde{f}\circ \tilde{j} = \tilde{j}\circ \tilde{g}.
$$

Remark 3.5. If  $f$  is normally expanding at  $j(\Sigma \times N)$  , then  $\mathbb{I}$  must be equal to  $\mathbb{N}$  . If  $f$  is normally hyperbolic but not normally expanding at  $j(\Sigma \times N)$  , then  $\mathbb{I}$  must be equal to  $\mathbb{Z}$

Theorem 3.4 is actually the main motivation to consider the class  $\operatorname{End}_{\sigma}^{r}(\Sigma \times N)$  Together with Example 3.2 and Proposition 3.8, it will enable to show that a finitely generated group of  $\operatorname{Diff}^{r}(N)$  can be robustly embedded into a fibration in any manifold  $M$  of dimension  $\geq 2$  , modulo perturbations in  $\operatorname{End}_{\sigma}^{r}(\Sigma \times N)$  . Let us prepare also the  $k$  - parameter  $(k\geq 1)$  version of this.

Definition 3.6. A family  $(g_{p})_{p\in B_{k}}$  of maps  $g_{p}$  in  $\operatorname{Emb}^{r}(\Sigma \times N,M)$  or  $\operatorname{End}^{r}(\Sigma \times N,M)$  is of class  $C^{r}$  if each map  $(p,x)\mapsto g_{p}(\mathcal{J},x)$  is of class  $C^{r}$  and depends continuously on  $\mathcal{J}\in \Sigma$ . Two such families are close if their corresponding latter maps are uniformly  $C^{r}$ - close. We denote by  $\widehat{\operatorname{Emb}}_{k}^{r}(\Sigma \times N,M)$  and  $\widehat{\operatorname{End}}_{\sigma k}^{r}(\Sigma \times N)$  these spaces of  $C^{r}$ - families of embeddings and endomorphisms.

COROLLARY 3.7. If  $(f_{p})_{p}$  is a  $C^{r}$ - family of maps  $f_{p}$  of  $M$  satisfying the assumption of Theorem 3.4 with  $\mathcal{L}_{p} = j_{p}(\Sigma \times N)$ , where  $(j_{p})_{p\in B_{k}}$  is a  $C^{r}$ - family of embeddings of  $\Sigma \times N$  into  $M$ , then for every  $(\tilde{f}_{p})_{p}$ $C^{r}$ - close to  $(f_{p})_{p}$ , there exists a family  $(\tilde{j}_{p})_{p}$  of embeddings  $C^{r}$ - close to  $(j_{p})_{p}$  and a family  $(\tilde{g}_{p})_{p}$  of endomorphisms of  $\Sigma \times N$ $C^{r}$ - close to  $(j_{p}^{- 1}\circ f_{p}\circ j_{p})_{p}$  such that

$$
\tilde{f}_{p}\circ \tilde{j}_{p} = \tilde{j}_{p}\circ \tilde{g}_{p}.
$$

Proof. We first consider the  $k$ - ball  $B_{k}$  as a subset of  $\widehat{B}_{k}\coloneqq P^{k}(\mathbb{R})$  and we extend the families  $(f_{p})_{p}$  and  $(j_{p})_{p}$  to  $C^{r}$ - families of maps parameterized by  $\widehat{B}_{k}$ . Then, we notice that  $\hat{f} \coloneqq (p,x)\mapsto (p,f_{p}(x))$  and  $\hat{j} \coloneqq (\mathcal{J},p,x)\mapsto j_{p}^{\mathcal{J}}(x)$  satisfies the assumption of Theorem 3.4 for the fibration  $\Sigma \times \widehat{N}$ , where  $\widehat{N} = \widehat{B}_{k}\times N$ . As for every  $C^{r}$ - perturbation  $(\tilde{f}_{p})_{p}$ , the map  $\hat{j} \coloneqq (p,x)\mapsto (p,\tilde{f}_{p}(x))$  is  $C^{r}$ - close to  $\hat{f}$ , there exists an embedding  $\hat{\hat{j}}$  of  $\Sigma \times \widehat{N}$  which is  $C^{r}$ - close to  $\hat{j}$  and which is left invariant by  $\hat{\hat{f}}$ .

Thus, for any  $p\in B_{k}$  and  $\mathcal{J}\in \Sigma$ , the submanifold  $\hat{\hat{j}} (\{\mathcal{J}\} \times \widehat{B}_{k}\times N)$  intersects transversally  $\{p\} \times M$  at a submanifold  $\tilde{j}_{p}^{\mathcal{J}}(N)$ . By transversality, this defines a  $C^{r}$ - family  $(\tilde{j}_{p}^{\mathcal{J}})_{p\in B_{k}}$  of embedding  $\tilde{j}_{p}^{\mathcal{J}}\colon N\hookrightarrow M$ , which depends continuously on  $\mathcal{J}\in \Sigma$ . Put  $\tilde{j}_{p}\colon (\mathcal{J},x)\mapsto \tilde{j}_{p}^{\mathcal{J}}(x)$ ; it is a  $C^{r}$ - embedding of  $\Sigma \times N$  into  $M$ . Also, the family  $(\tilde{j}_{p})_{p\in B_{k}}$  is of class  $C^{r}$ . Note that the submanifold  $\tilde{j}_{p}^{\mathcal{J}}(N)$  is sent by  $\tilde{f}_{p}$  into  $\tilde{j}_{p}^{\sigma (\mathcal{J})}(N)$ , since  $\hat{\hat{f}}$  leaves invariant  $\{p\} \times M$  and sends  $\hat{\hat{j}} (\{\mathcal{J}\} \times \widehat{B}_{k}\times N)$  into  $\hat{\hat{j}} (\{\sigma (\mathcal{J})\} \times \widehat{B}_{k}\times N)$ , while  $\{p\} \times j_{p}^{\mathcal{J}}(N) = \{p\} \times M\cap \hat{\hat{j}} (\{\mathcal{J}\} \times \widehat{B}_{k}\times N)$  and  $\{p\} \times j_{p}^{\sigma (\mathcal{J})}(N) = \{p\} \times M\cap \hat{\hat{j}} (\{\sigma (\mathcal{J})\} \times \widehat{B}_{k}\times N)$ .

The following enables to embed a finitely generated semi- group of circle diffeomorphisms into the periodic fibers of a normally hyperbolic fibration of any manifold  $M$  of dimension  $n\geq 2$ . A perturbation of this embedding persists is the sense of Theorem 3.4.

PROPOSITION 3.8. For any  $(g^{\alpha})_{\alpha}\in \operatorname{End}^{r}(N)^{\mathcal{A}}$  with  $N$  a circle and  $1\leqslant R\leqslant r\leqslant \infty$  with  $R< \infty$ , there are a  $C^{r}$ - map  $f$  of  $M$  and a fibration  $\mathcal{L} = j(\Sigma \times N)$  with  $j\in \operatorname{Emb}^{r}(\Sigma \times N,M)$  such that

(1) if  $n\geq 2$  and  $\mathbb{I} = \mathbb{N}$ , then the map  $f$  is  $R$ -normally expanding at  $\mathcal{L}$ ; 
(2) if  $n > 2$ ,  $\mathbb{I} = \mathbb{Z}$  and each  $g^{\alpha}$  is a diffeomorphism preserving the orientation, then  $f$  is a diffeomorphism  $R$ -normally hyperbolic at  $\mathcal{L}$ ; 
(3)  $g = j^{-1}\circ f\circ j$  is the canonical endomorphism associated with  $(g^{\alpha})_{\alpha \in \mathcal{A}}$  given by Example 3.2.

Similarly, for any  $((g_{p}^{\alpha})_{p\in \mathbb{B}_{k}})_{\alpha \in \mathcal{A}}\in \widehat{\mathrm{Emb}}_{k}^{r}(N)^{\mathcal{A}}$ , there are an embedding

$$
j\in \mathrm{Emb}^{r}(\Sigma \times N,M)
$$

and a  $C^r$ - family  $(f_{p})_{p}$  of maps  $f_{p}$  of  $M$  such that, for every  $p\in B_{k}$ , the maps  $f_{p}$  and  $\mathcal{L}\coloneqq j(\Sigma \times N)$  satisfy (1)- (3) with  $(g_{p}^{\alpha})_{\alpha \in \mathcal{A}}$ .

Proof. It suffices to prove this proposition in the case where  $M = (- 1,1)^{n - 1}\times N$  with  $f$  (resp. each  $f_{p}$ ) coincides with the identity nearby the boundary of  $M$ . Indeed, as  $N$  is a circle, the set  $(- 1,1)^{n - 1}\times N$  can be embedded into any  $n$ - manifold and the dynamics can be extended by the identity outside of this embedding. So, let us assume that  $M = (- 1,1)^{n - 1}\times N$ . Let us now focus on the parametric case (the parameter free version is obtained by taking  $k = 0$ ).

When  $\mathbb{I} = \mathbb{N}$ , let  $S$  be a smooth map of  $(- 1,1)^{n - 1}$  equal to the identity at the neighborhood of  $\partial [- 1,1]^{n - 1}$ , and such that  $S$  leaves invariant an expanding Cantor set  $K$  which is conjugate to the shift on  $\mathcal{A}^{\mathbb{N}}$ . Up to replacing  $S$  by an iterate and taking a subset of  $K$ , we may assume that the restriction of  $DS|_{K}$  is  $R$ - times more expanding than any derivatives of  $(g_{p}^{\alpha})_{\alpha \in \mathcal{A},p\in B_{k}}$ .

When  $n\geq 3$  and  $\mathbb{I} = \mathbb{Z}$ , let  $S$  be a smooth diffeomorphism of  $(- 1,1)^{n - 1}$  equal to the identity at the neighborhood of  $\partial [- 1,1]^{n - 1}$ , and such that  $S$  leaves invariant a hyperbolic horseshoe  $K$  which is conjugate to the shift  $\sigma$  on  $\mathcal{A}^{\mathbb{Z}}$ . We are going to construct  $f_{p}$  of the form:  $f_{p}\coloneqq (\mathcal{J},x)\mapsto (S^{m}(\mathcal{J}),f_{p}^{j}(x))$  for some  $m\geq 1$ . Up to replacing  $S$  by an iterate and taking a subset of  $K$ , we may assume that the restriction of  $DS$  to the stable and unstable directions of  $K$  are  $R$ - times more contracting and expanding than any derivative of  $(g_{p}^{\alpha})_{\alpha \in \mathcal{A},p\in B_{k}}$ .

FACT 3.9. There is a  $C^r$ - family  $(f_{p}^{j})_{j\in (- 1,1)^{n - 1},p\in B_{k}}$  of self- maps  $f_{p}^{j}$  of  $N$  such that for any  $p\in B_{k}$ :

(1)  $f_{p}^{j}$  coincides with the identity nearby the boundary of  $(-1,1)^{n - 1}$  
(2)  $f_{p}^{j} = g_{p}^{\alpha}$  if  $\mathcal{J}$  belongs to  $K$  and corresponds to an  $\mathcal{A}$  -sequence with  $a\in \mathcal{A}$  at the 0-position; 
(3) if for every  $p$  , the maps  $(g_{p}^{\alpha})_{\alpha \in \mathcal{A}}$  are orientation preserving diffeomorphims, then the maps  $f_{p}^{j}$  are orientation preserving diffeomorphims for every  $\mathcal{J}\in [-1,1]^{n - 1}$

Proof. The construction can be done using bump function and homotopies in the set of  $C^r$ - endomorphisms of  $N$  or  $C^r$ - diffeomorphisms preserving the orientation of  $N$ .

We can consider the immersion  $j\colon \Sigma \times N\to K^{\prime}\times N\subset K\times N\subset M$  which is  $R$ - normally expanding or hyperbolic for  $f_{p}\coloneqq (\mathcal{J},x)\mapsto (S(\mathcal{J}),f_{p}^{j}(x))$ .

Remark 3.10. In the proof of the latter proposition for the diffeomorphisms case, we may assume that the hyperbolic basic set  $K$  has unstable dimension 1, and that it is a subset of an attractor  $A$  (for instance using a Plykin attractor). Then, there is a neighborhood of  $N\times A$  which is sent into itself by the dynamics and on which the dynamics is partially hyperbolic. So, this neighborhood is  $C^{r - 1}$  - foliated by local strong stable manifolds of dimension  $\dim M - 2$  , by [22] or [33, Theorem 3.2]. Also, if  $f$  depends  $C^{r}$  - on a parameter, this foliation depends  $C^{r - 1}$  on the parameter.

It will be more comfortable while working with blenders to only deal with endomorphisms of  $\mathcal{A}^{\mathbb{N}}\times N$  . In order to do so, we consider the canonical projection  $\rho \colon \Sigma = \mathcal{A}^{\mathbb{Z}}\to \mathcal{A}^{\mathbb{N}}$  and put  $\mathcal{I}\sim \mathcal{I}^{\prime}$  if  $\rho (\mathcal{I}) = \rho (\mathcal{I}^{\prime})$  for  $\mathcal{I},\mathcal{I}^{\prime}\in \Sigma$  . Let

$$
\widetilde{\Sigma} \coloneqq \{(\mathcal{I},\mathcal{I}^{\prime})\in \Sigma^{2}:\mathcal{I}\sim \mathcal{I}^{\prime}\} .
$$

Proposition 3.11. Under the setting of Proposition 3.8 with  $\mathbb{I} = \mathbb{Z}$ , there exists a continuous family  $(\mathsf{hol}^{j,j^{\prime}})_{(j,j^{\prime})\in \widetilde{\Sigma}}$  of homeomorphisms of  $N$  such that

(1)  $\mathsf{hol}^{j,j^{\prime}}$  is the identity if  $\mathcal{I} = \mathcal{I}^{\prime}$  
(2)  $\mathsf{hol}^{\sigma (j),\sigma (j^{\prime})}\circ \tilde{g}^{j} = \tilde{g}^{j^{\prime}}\circ \mathsf{hol}^{j,j^{\prime}}$  for every  $(\mathcal{I},\mathcal{I}^{\prime})\in \widetilde{\Sigma}$  
(3) if  $\dim N = 1$  , then  $\mathsf{hol}^{j,j^{\prime}}$  is in  $\mathrm{Diff}^{r - 1}(N)$  and depends continuously on  $(\mathcal{I},\mathcal{I}^{\prime})\in \widetilde{\Sigma}$  Under the setting of Corollary 3.7 with  $\mathbb{I} = \mathbb{Z}$  , there exists a continuous family

$$
(\mathsf{hol}_{\mathsf{p}}^{j,j^{\prime}})_{p\in B_{k}}
$$

of homeomorphisms  $\mathsf{hol}_{\mathsf{p}}^{j,j^{\prime}}$  of  $N$  satisfying (1) and (2) with  $\tilde{g}_{p}$  for every  $p\in B_{k}$  . Also, if  $\dim N = 1$  , then  $(\mathsf{hol}_{p}^{j,j^{\prime}})_{p}$  is a  $C^{r - 1}$  - family of  $C^{r - 1}$  - diffeomorphisms and depends continuously on  $(\mathcal{I},\mathcal{I}^{\prime})\in \widetilde{\Sigma}$

Proof. We define  $\mathsf{hol}^{j,j^{\prime}}$  as the holonomy from  $\tilde{j}^{j}(N)$  and  $\tilde{j}^{j^{\prime}}(N)$  along the strong stable foliation defined in Remark 3.10.  $\square$

Given a section  $\iota \colon \mathcal{A}^{\mathbb{N}}\hookrightarrow \mathcal{A}^{\mathbb{Z}}$  of  $\rho$ , the latter proposition defines a semi- conjugacy between  $g$  and the map  $(\mathcal{I},x)\in \mathcal{A}^{\mathbb{N}}\times N\mapsto (\sigma (\mathcal{I}),g^{\iota (\mathcal{I})}(x))$ , and so enables to focus on the case  $\mathbb{I} = \mathbb{N}$ .

# 3.2. Intrinsic definition of  $(\lambda)$ -blender

The notion of blender was introduced by Bonatti and Diaz in [12], as a hyperbolic basic set for a  $C^{1}$ - self- map (resp. diffeomorphism)  $f$  of a manifold. Such are included in a normally expanding (hyperbolic) fibration, and so always included in a fibration  $\Sigma \times N$  embedded into  $M$ , whose fibers are either compact or weakly contracted by the dynamics.

The dynamics induced by  $f$  on this fibration is a map  $g\in \operatorname{End}_{\sigma}^{r}(\Sigma \times N)$  for a certain  $\sigma \in C^{0}(\Sigma ,\Sigma)$ . This leads us to propose an intrinsic definition of blender: it regards only the map  $g$ . For the sake of simplicity, we restrict our study to the case where  $\sigma \colon \Sigma \to \Sigma$  is the shift on  $\mathcal{A}^{\mathbb{I}}$ , with  $\mathbb{I} = \mathbb{N}$  or  $\mathbb{I} = \mathbb{Z}$ . In the case  $\mathbb{I} = \mathbb{Z}$ , using the holonomy along the strong stable manifolds defined in Proposition 3.11, we recall that the map  $g$  is semi- conjugated to one for which  $\mathbb{I} = \mathbb{N}$ . So, we will focus on the case  $\mathbb{I} = \mathbb{N}$ . For the sake of completeness, the standard definition of blender is recalled in Appendix A, it is not more general nor simpler to use than the intrinsic definition we shall introduce.

Let  $g\in \operatorname{End}_{\sigma}^{1}(\Sigma \times N)$  with  $\Sigma = \mathcal{A}^{\mathbb{N}}$ . A  $g$ - invariant compact subset  $\Lambda \subset \Sigma \times N$  is a basic set if it is transitive and locally maximal: it is the maximal invariant set in one of its neighborhood  $V_{\Lambda}$ . The basic set  $\Lambda$  is centrally contracting if  $g|\Lambda \cap \{\mathcal{I}\} \times N$  is contracting for every  $\mathcal{I}\in \Sigma$ . Then, for every  $C^1$ - perturbation  $\tilde{g}$  of  $g$ , the maximal invariant

$$
\tilde{\Lambda} \coloneqq \bigcap_{n\in \mathbb{Z}}\tilde{g}^{n}(V_{\Lambda})
$$

is called the continuation of  $\Lambda$ . One can show that it does not depend  $V_{\Lambda}$ , provided that  $\tilde{g}$  is sufficiently  $C^1$ - close to  $g$  and that  $\tilde{\Lambda}$  is a centrally contracting basic set for  $\tilde{g}$ . Let  $\overline{V}_{\Lambda}(\tilde{g})$  be the set of  $(v_{n})_{n< 0}\in V_{\Lambda}^{\mathbb{Z}^{- }}$  such that  $\tilde{g} (v_{n - 1}) = v_{n}$  for every  $n< - 1$ . By central contraction and local maximality of  $\tilde{\Lambda}$ , one can show that  $v_{n}\to \tilde{\Lambda}$  when  $n\to - \infty$ . Thus, the following is called a local unstable set of  $\tilde{\Lambda}$ :

$$
W_{\mathrm{loc}}^{u}(\tilde{\Lambda})\coloneqq \{v_{0}\in \Sigma \times N:\mathrm{there~exists~}(v_{n})_{n< 0}\in \overleftarrow{V}_{\Lambda}(\tilde{g})\mathrm{~with~}\tilde{g} (v_{-1}) = v_{0}\} .
$$

When  $\tilde{g} = g$ , we put

$$
W_{\mathrm{loc}}^{u}(\Lambda)\coloneqq W_{\mathrm{loc}}^{u}(\tilde{\Lambda}).
$$

When  $\tilde{g}\neq g$ , we say that  $W_{\mathrm{loc}}^{u}(\tilde{\Lambda})$  is the continuation of  $W_{\mathrm{loc}}^{u}(\Lambda)$ . The following is an intrinsic definition of the Bonatti- Diaz blender [12].

Definition 3.12. (Blender for  $\operatorname{End}_{\sigma}^{1}(\Sigma \times N)$ ) The centrally contracting, basic set  $\Lambda$  is a blender if a local unstable set  $W_{\mathrm{loc}}^{u}(\Lambda)$  has non- empty interior and for any subset  $K\Subset W_{\mathrm{loc}}^{u}(\Lambda)$ , for every  $C^1$ - perturbation  $\tilde{g}$  of  $g$ , the continuation  $W_{\mathrm{loc}}^{u}(\tilde{\Lambda})$  contains  $K$ .

Example 3.13. Let  $(g^{\ell})_{\ell \in \mathcal{B}_{0}}$  be the family of maps of Example 2.2. Let  $\mathcal{A}$  be a finite alphabet which contains  $\mathcal{B}_0\coloneqq \{- , + \}$ . Let  $g\in \operatorname{End}^{1}(\Sigma \times \mathbb{R})$  be such that  $g|_{\mathcal{B}_0^{\mathbb{N}}\times \mathbb{R}}$  is the canonical map associated with  $(g^{\ell})_{\ell \in \mathcal{B}_0}$  (see Example 3.2). Then, the set

$$
\Lambda = \mathcal{B}_0^{\mathbb{N}}\times [-1,1]
$$

is a blender for  $g$  and  $\Sigma \times [- 1,1]$  is a local unstable set of  $\Lambda$ .

Proof. Let  $V_{\Lambda}$  be the subset of points  $(\mathcal{I},x)\in \Sigma \times (- 2,2)$  such that the first letter of  $\mathcal{I}$  is in  $\mathcal{B}_{0}$  . It is a neighborhood of  $\Lambda$  , and so its maximal invariant set must contain  $\Lambda$  Also, the maximal invariant set of  $V_{\Lambda}$  must be included in  $\mathcal{B}_{0}^{\mathbb{N}}\times (- 2,2)$  , and so is equal to  $\Lambda$  by central contraction. Let  $K\coloneqq (- 1 + \eta ,1 - \eta)$  for  $\eta >0$  small.

By the open covering property proved in Example 2.2, for  $\tilde{g}$  sufficiently close to  $g$  for all  $\mathcal{I}_{0}\in \Sigma = \mathcal{A}^{\mathbb{N}}$  and  $x_{0}\in K$  , there exist  $\mathcal{U}_{- 1}\in \mathcal{B}_{0}$  and  $x_{- 1}\in K$  such that

$$
g^{\mathcal{I} - 1}(x_{-1}) = x_{0}
$$

with  $\mathcal{I}_{- 1}\in \sigma^{- 1}(\mathcal{I}_{0})$  with 0- coordinate equal to  $\mathcal{U}_{- 1}$  . We can iterate this process to construct a preorbit  $(\mathcal{I}_{- n},x_{- n})_{n\leqslant - 1}\in \overleftarrow{V}_{\Lambda}(\tilde{g})$  such that each  $x_{- n}$  is in  $K$  and

$$
g(\mathcal{I}_{-1},x_{-1}) = (\mathcal{I}_{0},x_{0}).
$$

Under the assumptions of Definition 3.12, let  $V_{\Lambda}$  be the neighborhood of  $\Lambda$  defining the local unstable set  $W_{\mathrm{loc}}^{u}(\Lambda)$  . Let  $\tilde{g}$  be a  $C^{1}$  - perturbation of  $g$  . The Lyapunov fiber  $\lambda (\tilde{g},\overleftarrow{v})$  of

$$
\overleftarrow{v} = (v_{j})_{j\leqslant 0}\in \overleftarrow{V}_{\Lambda}(\tilde{g})
$$

is the set of cluster values of

$$
\left(\frac{1}{m}\log |\partial_{x}\tilde{g}^{m}(v_{-m})|\right)_{m};
$$

this is an interval of  $\mathbb{R}$  . The Lyapunov fibration of  $W_{\mathrm{loc}}^{u}(\tilde{\Lambda})$  is

$$
\lambda (W_{\mathrm{loc}}^{u}(\tilde{\Lambda}))\coloneqq \bigcup_{\overleftarrow{v}\in \overleftarrow{V}_{\Lambda}(\tilde{g})}\{v_{0}\} \times \lambda (\tilde{g},\overleftarrow{v})
$$

Here is the counterpart of the notion of  $\lambda$  - blender introduced for finitely generated semi- groups of circle diffeomorphisms. This new notion is devoted to prove Theorem A using Theorem 1.8.

Definition 3.14. (  $\lambda$  - Blender for  $\operatorname{End}_{\sigma}^{1}(\Sigma \times N)$  ) A blender  $\Lambda$  for  $g\in \operatorname{End}^{1}(\Sigma \times N)$  is a  $\lambda$  blender if the Lyapunov fibration of a local unstable set  $W_{\mathrm{loc}}^{u}(\Lambda)$  has non- empty interior and, given any subset  $K\Subset\lambda(W_{\mathrm{loc}}^{u}(\Lambda))$  , for every  $C^{1}$  - perturbation of  $\tilde{g}$  , the Lyapunov fibration of the continuation  $W_{\mathrm{loc}}^{u}(\tilde{\Lambda})$  contains  $K$

A generalization of the following will be proved in Example 3.20.

Example 3.15. Let  $(g^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}}$  be the family of maps in Example 2.10. Let  $\mathcal{A}$  be a finite alphabet which contains  $\mathcal{B}_{0}^{\lambda}$  and  $\Sigma \coloneqq \mathcal{A}^{\mathbb{N}}$  .Let  $g\in \operatorname{End}^{1}(\Sigma \times \mathbb{R})$  be such that  $g|(\mathcal{B}_{0}^{\lambda})^{\mathbb{N}}\times P^{1}(\mathbb{R})$  is the canonical map associated with  $(g^{\ell})_{\ell \in \mathcal{B}_{0}}$  . Then,

$$
\Lambda = (\mathcal{B}_{0}^{\lambda})^{\mathbb{N}}\times [-1,1]
$$

is a  $\lambda$ - blender for  $g$ . Then, the set

$$
W_{\mathrm{loc}}^{u}(\Lambda) = \Sigma \times [-1,1]
$$

is a local unstable set of  $\Lambda$ , and its Lyapunov fibration is

$$
W_{\mathrm{loc}}^{u}(\Lambda)\times \left[\log \frac{2}{3} -\epsilon ,\log \frac{2}{3} +\epsilon \right]
$$

# 3.3. Intrinsic definition of  $C^{rr}$  -  $\lambda$  )-parablender

Let  $g = (g_{p})_{p\in B_{k}}$  be a  $C^{rr}$  - family of maps  $g_{p}\in \operatorname{End}_{\sigma}^{r}(\Sigma \times N)$  , for  $\Sigma = \mathcal{A}^{\mathbb{N}}$ $1\leq r< \infty$  and  $k\geq 0$  . For  $\mathcal{S}\in \Sigma$  and  $p\in B_k$  , let  $g_{p}^{j}$  be the second coordinate of the restriction  $g_{p}\big|_{\{\mathcal{S}\} \times N}$  Let  $g^{j} = (g_{p}^{j})_{p}$  . For every  $p_0\in B_k$  , we denote

$$
J_{p_0}^r g\coloneqq (\mathcal{J},J_{p_0}^r x)\in \Sigma \times J_{p_0}^r N\longmapsto (\sigma (\mathcal{J}),J_{p_0}^r g^{\mathcal{J}}(J_{p_0}^r x))\in \Sigma \times J_{p_0}^r N.
$$

Assume that  $g_{p_0}$  has a blender  $\Lambda_{p_0}$  which is locally maximal in a certain neighborhood  $V_{\Lambda}$  of  $\Lambda_{p_0}$  . Let  $W_{\mathrm{loc}}^{u}(\Lambda_{p_0})$  be the local unstable set of  $\Lambda_{p_0}$  , associated with  $V_{\Lambda}$  . Let  $\Sigma^{\prime}$  be the image of  $V_{\Lambda}$  via the first coordinate projection  $\Sigma \times N\rightarrow \Sigma$  . Let  $\overleftarrow{\Sigma}^{\prime}$  be the set of  $\sigma$  preorbits  $(\mathcal{J}_j)_{j< 0}\in \Sigma^{\prime \mathbb{Z}^- }$  and put  $\scriptstyle \mathcal{J}_0 = \sigma (\mathcal{J}_{- 1})$  . We choose a continuous family  $\Omega = (\Omega_{j})_{j\in \Sigma^{\prime}}$  such that  $\{(\mathcal{J},\omega_j)\colon \mathcal{J}\in \Sigma^{\prime}\}$  is included in  $V_{\Lambda}$  . Then, the set  $W_{\mathrm{loc}}^{u}(\Lambda_{p_0})$  is formed by the points  $\begin{array}{r}v(\underline{\mathcal{J}}) = \lim_{i\to +\infty}g_{p_0}^i (\mathcal{J}_{- i},\Omega_{\mathcal{J}_{- i}}) \end{array}$  among  $\underline{\mathcal{J}} = (\mathcal{J}_j)_{j< 0}\in \overleftarrow{\Sigma}^{\prime}$  . Note that

$$
v(\underline{\mathcal{J}}) = (\mathcal{J}_0,X_{p_0}(\underline{\mathcal{J}}))\quad \mathrm{with} X_{p_0}(\underline{\mathcal{J}}) = \lim_{i\to \infty}g_{p_0}^{\mathcal{J} - i}\circ \ldots \circ g_{p_0}^{s - 1}(\Omega_{\mathcal{J}_{-i}}) \mathrm{and} \mathcal{J}_0 = \sigma (\mathcal{J}_{-1}).
$$

This limit does not depend on  $\Omega$  . Also, for every  $p$  nearby  $p_0$  , the continuation  $W_{\mathrm{loc}}^{u}(\Lambda_{p})$  of  $W_{\mathrm{loc}}^{u}(\Lambda_{p_0})$  is formed by the points  $v(\underline{\mathcal{J}}) = (\mathcal{J}_0,X_p(\underline{\mathcal{J}}))$  , with

$$
X_{p}(\underline{\mathcal{J}}) = \lim_{i\to \infty}g_{p}^{\mathcal{J} - i\dots s - 1}(\Omega_{\mathcal{J}_{-i}}).
$$

Furthermore, the family  $(X_{p}(\underline{\mathcal{J}}))_{p}$  is of class  $C^r$  for every  $\underline{\mathcal{J}}\in \overline{\Sigma}^{\prime}$  , and depends continuously on  $\underline{\mathcal{J}}$  . Put

$$
J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda)\coloneqq \{(\mathcal{J}_0,J_{p_0}^r X(\underline{\mathcal{J}})):\underline{\mathcal{J}}\in \Sigma '\} \subset \Sigma \times J_{p_0}^r N.
$$

Similarly for  $\tilde{f} C^{r}$  - close to  $g$  and  $p$  close to  $p_0$  , we can define

$$
\widetilde{X}_{p}(\underline{\mathcal{J}}) = \lim_{i\to \infty}\widetilde{g}_{p}^{\mathcal{J} - i\dots s - 1}(\Omega_{\mathcal{J}_{-i}})
$$

and

$$
J_{p_0}^r W_{\mathrm{loc}}^u (\widetilde{\Lambda})\coloneqq \{(\mathcal{J}_0,J_{p_0}^r\widetilde{X} (\underline{\mathcal{J}})):\underline{\mathcal{J}}\in \Sigma '\} \subset \Sigma \times J_{p_0}^r N.
$$

Definition 3.16. (  $C^r$  - parablender for  $\widehat{\mathrm{End}_{\sigma ,k}^{r}}$  ) The continuation  $(\Lambda_{p})_{p}$  is called a  $C^r$  parablender at  $p_0$  if  $J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda)$  has non- empty interior and, for every  $K\Subset J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda)$  the continuation  $J_{p_0}^r W_{\mathrm{loc}}^u (\tilde{\Lambda})$  of  $J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda)$  of any sufficiently small  $C^r$  - perturbation  $\tilde{g}$  of  $g$  contains  $K$

We give an example below of parablender. Let us continue by introducing the  $C^r$  A- parablender. Now,  $N$  is a curve with tangent space identified to  $N\times \mathbb{R}$  . The Lyapunov fiber of  $(\mathcal{I}_0,J_{p_0}^r X(\underline{\mathcal{I}}))$  for  $\underline{\mathcal{I}}\in \overline{\Sigma}^{\prime}$  is the set  $\lambda (g,J_{p_0}^r X(\underline{\mathcal{I}}))$  of cluster values of

$$
\left(J_{p_0}^{r - 1}\frac{1}{i}\log |\partial_xg_p^i (\mathcal{I}_{-i},\Omega_{\mathcal{I}_{-i}})|\right)_{i > 0}.
$$

The following is the Lyapunov fibration of  $J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda)$

$$
\lambda (J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda))\coloneqq \bigcup_{\underline{\mathcal{I}}\in \overline{\Sigma}^{\prime}}\{(\mathcal{I}_0,J_{p_0}^r X(\underline{\mathcal{I}}))\} \times \lambda (g_0,J_{p_0}^r X(\underline{\mathcal{I}})).
$$

We notice that  $\lambda (J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda))$  is a compact subset of  $\Sigma \times J_{p_0}^r N\times J_{p_0}^{r - 1}\mathbb{R}$  .Here is the parametric counterpart of the  $\lambda$  - blender defined in Definition 3.14; it is devoted to prove Theorem B using Theorem 1.9. .

Definition 3.17. (  $\lambda$  - parablender for  $\widehat{\mathrm{End}_{\sigma,k}^{r}} (\Sigma \times N)$  ) The continuation  $(\Lambda_{p})_{p}$  of a blender is a  $C^r$  -  $\lambda$  - parablender at  $p_0$  if  $\lambda (J_{p_0}^r W_{\mathrm{loc}}^u (\Lambda))$  has non- empty interior and any subset  $K\Subset\lambda(J_{p_0}^r W_{\mathrm{loc}}^u(\Lambda))$  is contained in the Lyapunov fibration of  $J_{p_0}^r W_{\mathrm{loc}}^u(\tilde{\Lambda})$  for any sufficiently small  $C^r$  - perturbation  $(\tilde{g}_p)_p$  of  $(g_{p})_{p}$

Remark 3.18. We notice that  $\Lambda_{p_0}$  is a  $\lambda$  - blender for  $g_{p_0}$  and  $(\Lambda_{p})_{p}$  is a  $C^r$  - parablender at  $p = p_0$  for  $(g_{p})_{p}$  . When  $k = 0$ $(\Lambda_{p})_{p}$  is a  $C^r$  -  $\lambda$  - parablender at  $p_0$  if and only if  $\Lambda_{p_0}$  is a  $\lambda$  - blender for  $g_{p_0}$

As promised here is an example of  $C^r$  - parablender.

Example 3.19. Let  $(g_{p}^{\ell})_{p\in B_{k},\ell \in \mathcal{B}_{r}}$  be the family of maps of Example 2.6. Let  $\mathcal{A}$  be a finite alphabet which contains  $\mathcal{B}_r$  . Let  $(g_{p})_{p}\in \widehat{\mathrm{End}_{\sigma,k}^{r}} (\Sigma \times N)$  be such that  $g_{p}\big|_{\mathcal{B}_{r}^{\mathbb{N}}\times \mathbb{R}}$  is the canonical map associated with  $(g_{p}^{\ell})_{\ell \in \mathcal{B}_{r}}$  for every  $p\in B_k$  . Then, the set  $\Lambda_{0} = \mathcal{B}_{r}^{\mathbb{N}}\times [- 1,1]$  is a blender for  $g_{0}$  and its continuation for  $(g_{p})_{p}$  is a  $C^r$  - parablender at  $p = 0$  with a local unstable set satisfying

$$
J_{0}^{r}W_{\mathrm{loc}}^{u}(\Lambda)\coloneqq \Sigma \times \bigg\{\sum_{i\in E_{r}}\xi_{i}\cdot p^{i}:(\xi_{i})_{i}\in [-1,1]^{E_{r}}\bigg\} .
$$

We skip the proof of this example, since it is similar to the one for IFS and useless for the proof of main Theorem B. Let us focus on the following example.

Example 3.20. Let  $(g_{p}^{\mathcal{A}})_{p\in B_{k},\mathcal{A}\in \mathcal{B}_{r}^{\lambda}}$  be the family of maps in Example 2.13 for  $\epsilon >0$  sufficiently small. Let  $\mathcal{A}$  be a finite alphabet which contains  $\mathcal{B}_{r}$ . Let

$$
(g_{p})_{p}\in \widehat{\operatorname{End}_{\sigma ,k}^{r}} (\Sigma \times \mathbb{R})
$$

be such that  $g_{p}|_{(\mathcal{B}_{r}^{\lambda})^{\mathbb{N}}\times \mathbb{R}}$  is the canonical map associated with  $(g_{p}^{\mathcal{A}})_{\ell \in \mathcal{B}_{r}^{\lambda}}$  for every  $p\in B_{k}$ . Then, the set  $\Lambda_{0} = (\mathcal{B}_{r}^{\lambda})^{\mathbb{N}}\times [- 1,1]$  is a  $\lambda$ - blender for  $g_{0}$ , and its continuation for  $g = (g_{p})_{p}$  is a  $C^{r}$ -  $\lambda$ - parablender at  $p = 0$  with a local unstable set satisfying

$$
\begin{array}{l}{{(J_{0}^{r}W_{\mathrm{loc}}^{u}(\Lambda))}}\\ {{=\Sigma\times\Bigg\{\Bigg(\sum_{i\in E_{r}}\xi_{i}\cdot p^{i},\log\frac{2}{3}+\epsilon\sum_{i\in E_{r-1}}\lambda_{i}\cdot p^{i}\Bigg):(\xi_{i})_{i}\in[-1,1]^{E_{r}},(\lambda_{i})_{i}\in[-1,1]^{E_{r-1}}}}\end{array}
$$

Proof. Let  $V_{\Lambda}$  be the subset of points  $(\mathcal{J},x)\in \Sigma \times (- 2,2)$  such that the 0- coordinate of  $\mathcal{J}$  is in  $\mathcal{B}_{r}^{\lambda}$ . It is a neighborhood of  $\Lambda_{0}$ . For the same reasons as in Example 3.13, the local unstable set associated with this neighborhood is  $W_{\mathrm{loc}}^{u}(\Lambda_{0}) = \Sigma \times [- 1,1]$ . Let  $\Sigma^{\prime}$  be the subset of points in  $\Sigma$  whose 0- coordinate is in  $\mathcal{B}_{r}^{\lambda}$ . Let  $\overline{\Sigma}^{\prime}$  be the set of  $\sigma$ - preorbits  $(v_{j})_{j< 0}$  with  $v_{j}\in \Sigma^{\prime}$ . Let  $\Omega_{j} = 0$  for every  $\mathcal{J}\in \Sigma$ . As for Example 2.13, it is easy to see that the Lyapunov fibration  $\lambda (J_{0}^{r}W_{\mathrm{loc}}^{u}(\Lambda))$  has the above form. It remains to show that it is a  $C^{r}$ -  $\lambda$ - parablender. For  $\eta >0$  small, put

$$
K = \Sigma \times \Bigg\{\Bigg(\sum_{i\in E_{r}}\xi_{i}\cdot p^{i},\log \frac{2}{3} +\epsilon \sum_{i\in E_{r - 1}}\lambda_{i}\cdot p^{i}\Bigg):(\xi_{i})_{i}\in I^{E_{r}},(\lambda_{i})_{i}\in I^{E_{r - 1}}\Bigg\}
$$

with

$$
I\coloneqq [-1 + \eta ,1 - \eta ].
$$

Let  $\tilde{g}$  be a  $C^{r}$ - perturbation of  $g$ . Let us show for every  $(\mathcal{J}_{0},x_{0},\ell)\in K$  and  $n > 0$ , the existence of a sequence of letters  $(\ell_{j})_{- n\leqslant j< 0}\in (\mathcal{B}_{r}^{\lambda})^{n}$  and a sequence of points

$$
(\mathcal{J}_{j},x_{j},\ell_{j})_{-n\leqslant j< 0}\in K^{n}
$$

such that, with  $\ell_{0} = 0$  and  $\mathcal{J}_{j}\in \Sigma$  equal to the concatenation of  $\ell_{j}\ldots \ell_{- 1}$  with  $\mathcal{J}_{0}$ , the following conditions hold:

(1)  $J_{p_{0}}^{r}\tilde{g}^{\mathcal{A}_{i}}(x_{i}) = x_{i + 1}$  for every  $-n\leqslant i< 0$

(2)  $\ell_{-n} = J_{p_{0}}^{r - 1}(\log |\partial_{x}\tilde{g}_{p}^{n}(\mathcal{J}_{-n},x_{-n})|)_{p}\in \{n\cdot \ell +\sum_{i\in E_{r - 1}}\lambda_{i}\cdot p^{i}\colon \lambda_{i}\in [-2\epsilon ,2\epsilon ]\} .$

The step  $n = 0$  is obvious. Assume the result shown for  $n\geqslant 0$ . Then, by the covering property showed on in Examples 2.2 and 2.6, with  $\ell_{- n - 1}\in \mathcal{B}_{r}^{\lambda}$  being the vector whose coefficients are the sign of those of the polynomial  $(x_{- n}, - \log |\partial_{x}\tilde{g}_{p}^{n}(\mathcal{J}_{- n},x_{- n})| + n\cdot \ell)$ . Then, for the same reasons as for Examples 2.2 and 2.10, the induction hypothesis holds

true at step  $n + 1$ . Using that  $\tilde{g}$  is contracting nearby  $\Lambda$ , by Proposition 2.3(1), we have that

$$
J_{p_{0}}^{r}\tilde{g}^{j - i}\circ \dots \circ \tilde{g}^{j - 1}(\Omega_{j - i}) - J_{p_{0}}^{r}\tilde{g}^{j - i}\circ \dots \circ J_{p_{0}}^{r - 1}\tilde{g}^{j - 1}(x_{-i})
$$

is small when  $i$  is large. This implies directly the first limit and, by Cesàro means, the second one:

$$
\widetilde{X} (\underline{{\lambda}}) = \lim_{i\to \infty}J_{p_{0}}^{r}\widetilde{g}_{p}^{j - i}\circ \dots \circ \widetilde{g}_{p}^{j - 1}(x_{-i}) = x_{0}\quad \mathrm{and}\quad \lambda (\widetilde{g},J_{0}^{r}\widetilde{X} (\underline{{\lambda}})) = \lim_{i\to \infty}\frac{\ell_{-i}}{i} = \ell_{-i}
$$

# 4. Proof of the main theorems

We have introduced all the concepts and techniques needed to prove main Theorems A and B. Both proofs are similar: we will show that the sets  $D$  and  $\widehat{D}$  involved in Theorems 1.8 and 1.9 are locally dense. In order to do so, we are going to use  $\lambda$ - ( $C^{r}$ - para)- blender and implement the dynamical rescaling techniques of §2.4. The density in the proof of Theorem A will be done along 2- parameter families. This will enable to obtain even the local density of analytic maps with a normally hyperbolic, periodic circle at which  $f$  is parabolic.

# 4.1. Theorem A

Proof of Theorem A. It suffices to show that the closure of the set  $D$  of Theorem 1.8 has non- empty  $C^{r}$ - interior for any  $2 \leqslant r \leqslant \infty$  which intersects  $\operatorname {Diff}^{r}(M)$  when

$$
n = \dim M\geqslant 3.
$$

Let  $\mathcal{B}_{0}^{\lambda}$  and  $(g^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}}$  be as in Example 2.10. We consider the extension of these maps to the projective space  $P^{1}(\mathbb{R})$ . Let  $\mathcal{A} = \mathcal{B}_{0}^{\lambda} \cup \{\ell \}$  for a symbol  $\ell$ , and put

$$
g^{r} \colon x \in P^{1}(\mathbb{R}) \longmapsto \frac{3}{2} \frac{x}{x + 1} \in P^{1}(\mathbb{R}).
$$

By Proposition 3.8 with  $R = 2$  and  $r = \infty$ , there are  $j \in \operatorname {Emb}^{\infty}(\Sigma \times P^{1}(N), M)$  and a  $C^{\infty}$  self- map  $f$  of  $M$  (which is a diffeomorphism if  $n \geqslant 3$ ) which is  $R$ - normally expanding (or hyperbolic if  $n \geqslant 3$ ) at  $\mathcal{L} = j(\Sigma \times P^{1}(\mathbb{R}))$ , and such that  $g = j^{- 1} \circ f \circ j$  is the canonical map of  $\operatorname {End}_{\sigma}^{\infty}(\Sigma \times P^{1}(\mathbb{R}))$  associated with  $(g^{\mathcal{A}})_{\mathcal{A} \in \mathcal{A}}$  (see Example 3.2).

The idea is to apply a similar perturbation scheme as for Corollary 2.15. This leads us to unfold  $f$  into a 2- parameter family. Let  $W$  be a neighborhood of  $0 \in \mathbb{R}^{2}$  and for  $p = (u, v) \in W$ , let

$$
g_{p}^{\ell} \coloneqq x \longmapsto g^{\ell}(x - v) + v \quad \text{for all} \ell \in \mathcal{B}_{0}^{\lambda}
$$

and

$$
g_{p}^{\ell}\coloneqq x\longmapsto \exp (u)\cdot g^{\ell}(x).
$$

Note that zero is a fixed point of  $g_{p}^{\ell}$  with Lyapunov exponent  $\log {\frac{3}{2}} + u$ . It is repulsive for  $W$  is small.

Again by Proposition 3.8, there is a  $C^{\infty}$ - family  $(f_{p})_{p\in W}$  of self- maps such that  $f_{0} = f$  and such that  $f_{p}$  leaves invariant  $\mathcal{L}$  and satisfies  $g_{p} = j^{- 1}\circ f_{p}\circ j$  is the canonical endomorphism of  $\Sigma \times P^{1}(\mathbb{R})$  associated with  $((g_{p}^{\alpha})_{p\in W})_{\alpha \in \mathcal{A}}$ .

Note that given any  $C^{R}$ - neighborhood  $\mathcal{M}_{W}$  of  $(f_{p})_{p}$ , the set  $\mathcal{M} = \{\tilde{f}_{0};(\tilde{f}_{p})_{p}\in \mathcal{M}_{W}\}$  is a neighborhood of  $f$ . Thus, it suffices to show that for  $\mathcal{M}_{W}$  sufficiently small, for every  $(\tilde{f}_{p})_{p}\in \mathcal{M}_{W}$ , there is an arbitrarily small parameter  $p$  such that  $\tilde{f}_{p}$  has a periodic fiber at which it is parabolic. Indeed, this defines a set of self- maps of  $M$  whose closure contains  $\mathcal{M}$ .

Let  $(\tilde{j}_{p})_{p}$  be the family of embeddings given by Corollary 3.7, and let

$$
\tilde{g}_{p}\coloneqq \tilde{j}_{p}^{-1}\circ \tilde{f}_{p}\circ \tilde{j}_{p}\in \mathrm{End}_{\sigma}^{R}(\Sigma \times P^{1}(\mathbb{R})).
$$

Recall that  $(\tilde{g}_{p})_{p}$  is  $C^{R}$ - close to  $(g_{p})_{p}$  when  $\mathcal{M}_{W}$  is small and  $\tilde{g}_{p}$  is of the form

$$
\tilde{g}_{p}(\mathcal{I},x) = (\sigma (\mathcal{I}),\tilde{g}_{p}^{\mathcal{I}}(x)),
$$

Let us simplify the setting.

FACT 4.1. Up to a reparametrization of  $\Sigma \times P^{1}(\mathbb{R})$  depending  $C^{2}$  on  $p$ , we may assume that for every  $\mathcal{I}\in \Sigma$  whose 0- coordinate is  $\ell$ , we have  $g_{p}^{\mathcal{I}}(0) = 0$  for every  $p$  small.

Proof. We define the operator  $(x_{p}^{\mathcal{I}})_{\mathcal{I}\in \Sigma}\mapsto (\tilde{x}_{p}^{\mathcal{I}})_{\mathcal{I}\in \Sigma}$ , where  $\tilde{x}_{p}^{\mathcal{I}} = 0$  if the first letter of  $\mathcal{I}$  is not  $\ell$  and  $\tilde{x}_{p}^{\mathcal{I}} = (\tilde{g}_{p}^{\mathcal{I}})^{- 1}(x_{p}^{\sigma (x)})$  otherwise. It is a contracting operator at the neighborhood of  $(0)_{\mathcal{I}\in \Sigma}$ . Let  $(\tilde{O}_{p}^{\mathcal{I}})_{\mathcal{I}\in \Sigma}$  be its fixed point. It depends  $C^{2}$  on  $p$ , since the operator does. Also, when  $\tilde{g} = g$ , we have  $(\tilde{O}_{p}^{\mathcal{I}})_{\mathcal{I}\in \Sigma} = (0)_{\mathcal{I}\in \Sigma}$  for every  $p$ , thus  $(\tilde{O}_{p}^{\mathcal{I}})_{\mathcal{I}\in \Sigma}$  is  $C^{2}$ - small. Thus, using a coordinate change via a translation by  $\tilde{O}_{p}^{\mathcal{I}}$ , we obtain the sought property.

The idea is to apply a variation of the proof of Proposition 2.14. This involves the space  $\mathcal{P}_{m}$  of  $2m$ - periodic points  $\mathcal{I}\in \Sigma$  of the form  $(\ell_{m}^{\mathcal{I}}\circ \ell^{m})^{\infty}$ : their letters at the positions  $0,\ldots ,m - 1$  form the word  $\ell_{m}\in (\mathcal{B}_{0}^{\lambda})^{m}$ , the  $m$  next letters are  $\ell$ . We will fix  $m\geqslant 1$  and  $\mathcal{I}\in \mathcal{P}_{m}$  in function of the perturbation  $(\tilde{g}_{p})_{p}$  of  $(g_{p})_{p}$ , and more precisely the properties of the following maps:

$$
\tilde{g}_{p}^{\ell_{m}}\coloneqq \tilde{g}_{p}^{\ell_{m} - 1}\circ \dots \circ \tilde{g}_{p}^{\ell^{0}}\mathrm{~and~}\tilde{g}_{p}^{\ell^{m}}\coloneqq \tilde{g}_{p}^{\ell^{2m - 1}}\circ \dots \circ \tilde{g}_{p}^{\ell^{m}},\mathrm{~with~}\ell^{j}\coloneqq \sigma^{j}(\ell) \tag{4.1}
$$

Note that when  $\tilde{g} = g$ , it holds  $\tilde{g}_{p}^{\ell_{m}}\coloneqq x\mapsto g^{\ell_{m}}(x - v) + v$  where  $g^{\ell_{m}}$  is the element of the group spanned by  $(g^{\ell})_{\ell \in \mathcal{B}_{0}^{\lambda}}$  and  $\tilde{g}_{p}^{\ell_{m}} = (g_{p}^{\ell})^{m}$  for every  $p\in W$ .

Hence, as  $W$  is small,  $\tilde{g}_{p}^{\ell m}$  is a composition of contractions of  $[- 2,2]$  into its interior. Let  $\tilde{x}_{p}(\ell_{m})\coloneqq \tilde{g}_{p}^{\ell_{m}}(0)$ . On the other hand, by Fact 4.1, the map  $(\tilde{g}_{w}^{\ell^{m}})$  fixes the point zero. Let  $\tilde{\lambda}_{p}(\ell_{m})$  and  $\tilde{\lambda}_{p}(\ell^{m})$  be the Lyapunov exponents of these fixed points:

$$
\tilde{\lambda}_{p}(\ell_{m}) = \frac{1}{m}\log |D_{0}\tilde{g}_{p}^{\ell_{m}}| \quad \text{and} \quad \tilde{\lambda}_{p}(\ell^{m}) = \frac{1}{m}\log |D_{0}\tilde{g}_{p}^{\ell^{m}}|. \tag{4.2}
$$

Here is the generalization of Proposition 2.14.

PROPOSITION 4.2. For  $\mathcal{M}_W$  small enough, for every  $(\tilde{f}_p)_p\in \mathcal{M}_W$ , if there exist  $(\ell_{m}\cdot \ell^{m})^{\infty}\in \mathcal{P}_{m}$  with  $m$  large and  $p\in W$  small such that

$$
\tilde{x}_{p}(\ell_{m}) = 0 \quad \text{and} \quad \tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}) = 0,
$$

then the map  $\breve{h} \coloneqq \breve{g}_{p}^{\ell^{m}}\circ \tilde{g}_{p}^{\ell_{m}}$  is parabolic.

The proof is very similar to Proposition 2.14 and done below. Hence, by Proposition 4.2 and Theorem 1.8, Theorem A is a consequence of the next claim.

CLAIM 4.3. For  $\mathcal{M}_W$ $C^R$  small enough, for every  $(f_{p})_{p}\in \mathcal{M}_{W}$ , there exist  $p\in W$  small and  $(\ell_{m}\cdot \ell^{m})^{\infty}\in \mathcal{P}_{m}$  with  $m$  large such that

$$
\tilde{x}_{p}(\ell_{m}) = 0 \quad \text{and} \quad \tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}) = 0.
$$

Proof. First let us show that we can restrict our proof to the case where  $\mathbb{I} = \mathbb{N}$ . Indeed, if  $\mathbb{I} = \mathbb{Z}$ , by Proposition 3.11, for every  $(\tilde{f}_p)\in \mathcal{M}_W$  and every  $\mathcal{J}\in \Sigma$ , there exists a  $C^{R - 1}$ - family  $(\mathsf{hol}_{p}^{J})_{p}$  depending continuously on  $\mathcal{J}\in \Sigma$  such that

$$
\mathsf{hol}_p^{\sigma^{(j)}}\circ \tilde{g}_p^j = \tilde{g}_p^{\iota \circ \rho^{(j)}}\circ \mathsf{hol}_p^{j},
$$

with  $\rho \colon \mathcal{A}^{\mathbb{Z}}\to \mathcal{A}^{\mathbb{N}}$  is the canonical retraction and  $\iota \colon \mathcal{A}^{\mathbb{N}}\to \mathcal{A}^{\mathbb{Z}}$  is the section which sends  $(a_{i})_{i\geq 0}$  to  $(a_{i})_{i\in \mathbb{Z}}$  with  $a_{j} = \ell$  for every  $j< 0$ . As  $(\tilde{g}_{p}^{\iota \circ \rho^{(j)}})_{p}$  is  $C^R$  close to  $(g_{p}^{\iota \circ \rho^{(j)}})_{p} = (g_{p}^{j})_{p}$ , the family  $(\tilde{g}_{p})_{p}$  is  $C^{R - 1}$ - conjugated to a family of endomorphisms of  $\mathcal{A}^{\mathbb{N}}\times P^{1}(\mathbb{R})$  which is  $C^R$ - close to the canonical family of endomorphisms associated with  $(g_{p}^{a})_{p}$ . Note that this is a  $C^R$  bound although the conjugacy is  $C^{R - 1}$ . As the conclusion of the Claim is invariant by  $C^{1}$ - intrinsic conjugacy and  $R = 2$ , it suffices to show the following:

CLAIM 4.4. Let  $\Sigma = \mathcal{A}^{\mathbb{N}}$ . For every  $(\tilde{g}_{p})_{p}$  in a  $C^R$ - small neighborhood  $\mathcal{N}_W$  of  $(g_{p})_{p}$ , there exist  $p\in W$  arbitrarily small and  $(\ell_{m}\cdot \ell^{m})^{\infty}\in \mathcal{P}_{m}$  with  $m$  large such that

$$
\tilde{x}_{p}(\ell_{m}) = 0 \quad \text{and} \quad \tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}) = 0.
$$

Let  $\ell^{\infty} = \ell \ell \ell \ldots \in \Sigma$  be the  $\sigma$ - fixed point whose  $\mathcal{A}$ - spelling has only the letter  $\ell$ . Given  $(\tilde{g}_{p})_{p}\in \mathcal{N}_{W}$ , by Fact 4.1, the point zero is fixed and repulsive for  $\tilde{g}_{p}^{\ell^{\infty}}$ . Let

$$
\tilde{\lambda}_{p}(\ell^{\infty})\coloneqq \log |D_{0}g_{p}^{\ell^{\infty}}|.
$$

FACT 4.5. When  $\mathcal{N}_W$  is small,  $(\tilde{\lambda}_{p}(\ell^{\infty}))_{p}$  is  $C^{R - 1}$  - close to  $\left(\log {\frac{3}{2}} + u\right)_{p = (u,v)}$

Let  $V_{\Lambda}\subset \Sigma \times P^{1}(\mathbb{R})$  be formed by the points  $(\mathcal{J},x)\in \Sigma \times (- 2,2)$  such that the 0- coordinate of  $\mathcal{J}$  is in  $\mathcal{B}_{0}^{\lambda}$  . By Example 3.15, the  $g$  - maximal invariant set of  $V_{\Lambda}$  is a  $\lambda$  - blender  $\Lambda$  , and the Lyapunov fibration of  $W_{\mathrm{loc}}^{u}(\Lambda) = \Sigma \times [- 1,1]$  contains  $\left(c^{\infty},0,\log {\frac{2}{3}}\right)$  in its interior. Thus, for  $\mathcal{N}_W$  sufficiently small, for every  $(\tilde{g}_{p})_{p}\in \mathcal{N}_{W}$  , there is a  $\tilde{g}_{0}$  - preorbit  $\overleftarrow{v} = (v_{j})_{j\leqslant 0}\in \overleftarrow{V}_{\lambda}(\tilde{g})$  such that

$$
v_{0} = (c^{\infty},0)\quad \mathrm{and}\quad \lambda_{0}(\tilde{g}_{0},\overleftarrow{v}) + \tilde{\lambda}_{0}(e^{\infty}) = 0. \tag{4.3}
$$

The  $\Sigma$  - coordinate of  $v_{m}$  is of the form

$$
\left(a_{-m},\dots,a_{-1},\ell ,\dots,\ell ,\dots\right)\in \Sigma ,
$$

with  $\ell_{m}\coloneqq a_{- m}\ldots a_{- 1}\in \mathcal{B}_{0}^{\lambda})^{m}$  . Fix  $(\ell_{m}\cdot \ell^{m})^{\infty}\in \mathcal{P}_{m}$  for a large  $m$

LEMMA 4.6. We have

$$
\lim_{m\to \infty}\tilde{x}_{0}(\ell_{m}) = 0\quad a n d\quad \lim_{m\to \infty} - \tilde{\lambda}_{0}(\ell_{m}) = \tilde{\lambda}_{0}(\ell^{\infty}) = \lim_{m\to \infty}\tilde{\lambda}_{0}(\ell^{m}).
$$

Proof. Most of maps in the composition  $\tilde{g}_{0}^{\ell \cdot (\ell_{m}\cdot \ell^{m})^{\infty}}\circ \dots \circ \tilde{g}_{0}^{\ell^{m}\cdot (\ell_{m}\cdot \ell^{m})^{\infty}}$  are close to  $\tilde{g}_{0}^{\infty}$  when  $m$  is large, so are the derivatives at zero. In view of (4.1) and (4.2), this proves that

$$
\lim_{m\to \infty}\tilde{\lambda}_{0}(\ell^{m}) = \tilde{\lambda}_{0}(\ell^{\infty}).
$$

The map  $\tilde{g}_{0}^{\ell_{m}}$  is the composition

$$
\tilde{g}_{0}^{\ell_{1}\cdot (\ell^{m}\cdot \ell_{m})^{\infty}}\circ \dots \circ \tilde{g}_{0}^{\ell_{m}\cdot (\ell^{m}\cdot \ell_{m})^{\infty}},
$$

with  $\ell_{j}\coloneqq a_{- j}\ldots a_{- 1}$  . Each of the maps  $\tilde{g}_{0}^{\ell_{j}\cdot (\ell^{m}\cdot \ell_{m})^{\infty}}$  is a contraction of  $[- 2,2]$  which is uniformly close to  $\tilde{g}_{0}^{\ell_{j}\cdot \ell^{\infty}}$  when  $m$  is large. Thus, the iterates of zero under these respective maps are uniformly close when  $m$  is large. This proves that  $\tilde{x}_{0}(\ell_{m})$  is close to  $\tilde{g}_{0}^{\ell_{1}\cdot \ell^{\infty}}\circ \dots \circ \tilde{g}_{0}^{\ell_{m}\cdot \ell^{\infty}}(0)$  when  $m$  is large. Also, as  $\tilde{g}_{0}^{\ell_{1}\cdot \ell^{\infty}}\circ \dots \circ \tilde{g}_{0}^{\ell_{m}\cdot \ell^{\infty}}$  is a large contraction of  $(- 2,2)$  which sends the  $x$  - coordinate  $x_{m}\in (- 2,2)$  of  $v_{m}$  to the  $x$  - coordinate of  $v_{0}$  which is zero by (4.3). So,  $\begin{array}{r}{\lim_{m\to \infty}\tilde{x}_{0}(\ell_{m}) = 0} \end{array}$  by (4.3). Note that this argument implies that most of the iterates of  $x_{m}$  and zero under  $\tilde{g}_{0}^{\ell_{1}\cdot \ell^{\infty}}\circ \dots \circ \tilde{g}_{0}^{\ell_{m}\cdot \ell^{\infty}}$  are close, and these are close to the iterates of zero under  $\tilde{g}_{0}^{\ell_{1}\cdot (\ell^{m}\cdot \ell_{m})^{\infty}}\circ \dots \circ \tilde{g}_{0}^{\ell_{m}\cdot (\ell^{m}\cdot \ell_{m})^{\infty}}$  . So are the derivatives at these points. This proves that

$$
\lim_{m\to \infty}\tilde{\lambda}_{0}(\ell_{m}) = \lambda_{0}(\tilde{g}_{0},\overleftarrow{v}),
$$

which is equal to  $- \tilde{\lambda}_{0}(\ell^{\infty})$  by (4.3).

The later statement and proof were done at the parameter  $p = 0$ , but can be done at any  $p \in W$ . We also obtain the convergence of the parametric jets for the same reasons. This gives the following.

LEMMA 4.7. For every  $p_0 \in W$ , with  $\widetilde{G}^m = (\widetilde{G}_p^m)_p$  and  $\widetilde{G}_p^m \coloneqq \widetilde{g}_p^{\ell_1 \cdot \ell^{\infty}} \circ \ldots \circ \widetilde{g}_p^{\ell_m \cdot \ell^{\infty}}$ , we have

$$
\begin{array}{r l} & {J_{p_{0}}^{R}(\widetilde{x}_{p}(\ell_{m}))_{p}\underset {m\rightarrow \infty}{\approx}J_{p_{0}}^{R}\widetilde{G}^{m}(0),}\\ & {\quad J_{p_{0}}^{R - 1}\widetilde{\lambda}_{0}(\ell_{m}^{\infty})_{m\rightarrow \infty}\underset {m\rightarrow \infty}{\approx}J_{p_{0}}^{R - 1}\frac{1}{m}\log |D_{0}\widetilde{G}^{m}|,}\\ & {\quad J_{p_{0}}^{R - 1}\widetilde{\lambda} (\ell^{\infty}) = \underset {m\rightarrow \infty}{\lim}J_{p_{0}}^{R - 1}\widetilde{\lambda} (\ell^{m}).} \end{array}
$$

We recall that  $R = 2$ . Let  $\underline{\ell} = (\ell_j \cdot \ell^{\infty})_{j < 0} \in \overleftarrow{\Sigma} '$ . By definition,

$$
J_{p_0}^R \widetilde{X} (\underline{\ell}) \quad \text{and} \quad \lambda (\widetilde{g}, J_{p_0}^R \widetilde{X} (\underline{\ell}))
$$

are the limit when  $m \to \infty$  of

$$
J_{p_0}^R \widetilde{G}^m (0) \quad \text{and} \quad J_{p_0}^{R - 1} \frac{1}{m} \log |D_0 \widetilde{G}^m|,
$$

respectively. Hence, by the latter lemma, the derivative  $\partial_p (\widetilde{x}_p (\ell_m))_p$  is close to  $\partial_p G^m (0)$  and  $\partial_p \widetilde{\lambda}_0 (\ell_m)$  is close to  $\partial_p \lambda (\widetilde{g}, J_{p_0}^R X(\underline{\ell}))$ . As

$$
G_p^m (0) = \lim_{j \to \infty} g^{\ell_j \dots \ell_{-1}} (-v) + v = \lim_{j \to \infty} g^{\ell_j \dots \ell_{-1}} (0) + v,
$$

its derivative is close to the second coordinate projection  $p = (u,v)\mapsto v$  .Also, we have that  $\partial_{p}\lambda (\tilde{g},J_{p_{0}}^{R}X(\underline{{\ell}}))$  is zero. Thus,  $\partial_{p}(\widetilde{\lambda} (\ell_{m}),\widetilde{x} (\ell_{m}))$  is close to the first coordinate projection. On the other hand,  $\partial_{p}\widetilde{\lambda} (\ell^{m})$  is close to  $\partial_{p}\widetilde{\lambda} (\ell^{\infty})$  , which is close to  $\partial_{p}\lambda (\ell^{\infty}) =$ $(u,v)\mapsto u$  . Thus, the derivative of the following function is close to the identity:

$$
\Upsilon_m \colon p = (u, v) \in W \longmapsto (\widetilde{\lambda}_p (\ell^m) + \widetilde{\lambda}_p (\ell_m), \widetilde{x}_p (\ell_m)).
$$

By Lemma 4.6, for  $m$  large, the point  $\Upsilon_{m}(0)$  is small. Thus, by the local inversion theorem, for  $m$  large enough, there exists  $p$  small such that  $\Upsilon_{m}(p) = 0$ . This proves Claim 4.4.  $\square$

Proof of Proposition 4.2. First note that, when  $(\tilde{g}_p)_p$  is  $C^2$ - close to  $(g_p)_p$  and  $p \in W$  is small, then  $\tilde{g} \coloneqq \tilde{g}_p$  is  $C^2$ - close to  $g = g_0$ . We recall that  $g^e$  is conjugate to  $x \mapsto \frac{3}{2} x$  via  $h(x) = x / (2x + 1)$ . For the same reasons as for Proposition 2.14, the following counterpart of Claim 2.16 implies Proposition 4.2.

CLAIM 4.8. Given  $\tilde{g} C^{2}$ - close to  $g$  and  $\mathcal{S} \in \mathcal{P}_{n}$  with  $n$  large, if  $\tilde{g}^{\ell_{n}}(0) = 0$  and the fixed point zero is parabolic for  $\tilde{h} \coloneqq \tilde{g}^{\ell^{m}} \circ \tilde{g}^{\ell_{n}}$ , then the restrictions to  $\left[- \frac{3}{2}, \frac{3}{2}\right]$  of  $\tilde{h}$  and  $h$  are  $C^{2}$ - close.

The following is the counterpart of Sternberg's Theorem 2.17.

LEMMA 4.9. There exist  $\tilde{h}_{1}, \tilde{h}_{2} \in C^{2}([- 2,2], \mathbb{R})$  which are  $C^{2}$ - close to  $h|_{[- 2,2]}$  and such that  $\tilde{h} (0) = 0$ ,  $D_{0} \tilde{h} (0) = 1$  and

$$
\tilde{h}_{1} = \tilde{g}^{\ell^{m}} \circ \tilde{h}_{2} \circ \left(D_{0} \tilde{g}^{\ell^{m}}\right)^{-1} |_{[-2,2]}.
$$

We show the latter lemma below. On the other hand the proof of the next lemma is skipped since it is the same as for Lemma 2.18.

LEMMA 4.10. The map  $\Phi = D_{0} \tilde{g}^{\ell^{m}} \circ \tilde{h}_{2}^{- 1} \circ \tilde{g}^{\ell_{m}} |_{[- 2,2]}$  is  $C^{2}$ - close to the identity.

By the latter lemma, the image by  $\Phi$  of  $\left[- \frac{5}{3}, \frac{5}{3}\right]$  is included in  $[- 2,2]$ . Thus, we can use Lemma 4.9 to obtain that the map  $\tilde{h} |_{[- 3 / 2,3 / 2]}$  is equal to the composition of  $\tilde{h}_{1}$ , which is  $C^{2}$ - close to  $h$  with a map  $\Phi C^{2}$ - close to the identity. This proves the claim.

Proof of Lemma 4.9. Let  $B$  be the set of continuous families  $(h^{j})_{j \in \Sigma}$  of  $C^{2}$ - diffeomorphisms  $h^{j}$  of  $[- 2,2]$  into  $\mathbb{R}$  such that  $h^{j}(0) = 0$  and  $D_{0} h^{j} = 1$ . We notice that  $B$  endowed with the  $C^{2}$ - distance is complete. We consider the operator

$$
\Psi \colon H = (h^{j})_{j \in \Sigma} \in B \longmapsto (\Psi (H)^{j})_{j} \in B,
$$

with

$$
\Psi (H)^{j} = \tilde{g}^{\ell^{j}, j} \circ h^{\ell^{j}, j} \circ \left(D_{0} \tilde{g}^{\ell^{j}, j}\right)^{-1},
$$

where  $\{\ell \} \times \mathcal{A}^{\mathbb{N}}$  and  $\mathcal{B}_0^\lambda \times \mathcal{A}^\mathbb{N}$  are the subsets of  $\mathcal{A}^{\mathbb{N}}$  formed by points whose first letters are in  $\{\ell \}$  and  $\mathcal{B}_0^\lambda$ , respectively. The map  $\Psi$  has a contracting iterate; let  $(\tilde{h}^{j})_{j}$  be its fixed point (which depends continuously on  $\tilde{g}$ ). It satisfies

$$
\tilde{h}^{j} = \tilde{g}^{\ell^{j}, j} \circ \tilde{h}^{\ell^{j}, j} \circ \left(D_{0} \tilde{g}^{\ell^{j}, j}\right)^{-1} = \tilde{g}^{\ell^{j}, j} \circ \ldots \circ \tilde{g}^{\ell^{m}, j} \circ \tilde{h}^{\ell^{m}, j} \circ \left(D_{0} \tilde{g}^{\ell^{j}, j} \circ \ldots \circ D \tilde{g}^{\ell^{m}, j}\right)^{-1}.
$$

Thus, with  $\mathcal{I} = (\ell_{m} \cdot \ell^{m})^{\infty}$  and  $\tilde{g}^{\ell^{m}}$  defined in (4.1) (p.240), we obtain

$$
\tilde{h}^{(\ell_{m} \cdot \ell^{m})^{\infty}} = \tilde{g}^{\ell^{m}} \circ \tilde{h}^{(\ell^{m} \cdot \ell_{m})^{\infty}} \circ \left(D_{0} \tilde{g}^{\ell^{m}}\right)^{-1}.
$$

We conclude by putting  $\tilde{h}_{1} = \tilde{h}^{(\ell_{m} \cdot \ell^{m})^{\infty}}$  and  $\tilde{h}_{2} = \tilde{h}^{(\ell^{m} \cdot \ell_{m})^{\infty}}$ .

Let us assume that  $M$  is an analytic manifold of dimension  $\geq 2$ . Let us choose a complex extension  $\tilde{M}$  of  $M$ . For  $\epsilon > 0$ , let  $\tilde{M}_{\epsilon}$  be the  $\epsilon$ - neighborhood of  $M$  in  $\tilde{M}$ . Let  $C_{\epsilon}^{\omega}(M, M)$  be the space of analytic maps from  $M$  into  $M$  whose analytic extension is well defined from  $\tilde{M}_{\epsilon}$  into  $\tilde{M}$  and  $C^{0}$ - bounded. This space is endowed with the uniform  $C^{0}$ - norm. The following is a consequence of the latter proof.

COROLLARY 4.11. For  $e > 0$  sufficiently small, there are locally dense sets  $D_{p}$  and  $D_{r}$  in  $C_{\epsilon}^{\omega}(M,M)$  formed by maps which display a normally hyperbolic smooth circle on which they act respectively as parabolic maps and Diophantine smooth rotations. Moreover,  $D_{p}$  and  $D_{r}$  are formed by diffeomorphisms if  $n \geq 3$ .

Proof. The set of 2- parameter  $C_{\epsilon}^{\omega}$  - families intersected with  $\mathcal{M}_{W}$  is an open set  $\mathcal{M}_{W,\epsilon}^{\omega}$  . Also, the set  $\mathcal{M}_{\epsilon}^{\omega} = \{\tilde{f}_{0},(\tilde{f}_{p})_{p}\in \mathcal{M}_{W,\epsilon}^{\omega}\}$  is open. For every  $\tilde{f}_{0}\in \mathcal{M}_{\epsilon}^{\omega}$  , by Proposition 4.2 and Claim 4.3, there exist  $p$  small and  $m\geq 1$  such that  $\tilde{f}_{p}^{2m}$  restricted to the fiber of  $(\ell_{m},\ell^{m})^{\infty}$  is a parabolic map  $\breve{h}$  . This implies the density in  $\mathcal{M}_{\epsilon}^{\omega}$  of analytic dynamics leaving invariant normally hyperbolic, periodic circles at which they are parabolic.

Now take  $p^{\prime} = p + (0,v^{\prime})$  with  $v^{\prime} > 0$  small. Then, the restriction  $\breve{h}_{v^{\prime}}$  of  $\tilde{f}_{p^{\prime}}^{2m}$  restricted to the fiber of  $(\ell_{m},\ell^{m})^{\infty}$  satisfies  $x\leqslant \breve{h} (x)< \breve{h}_{v^{\prime}}(x)$  for every  $x\in P^{1}(\mathbb{R})$  , so  $\breve{h}_{v^{\prime}}$  has none fixed points, and so its rotation number differs to the one of  $\breve{h}$  which is zero. Thus, by continuity of the rotation number, there exists  $v^{\prime}$  small such that the rotation number of  $\breve{h}_{v^{\prime}}$  is Diophantine. This implies the density in  $\mathcal{M}_{\epsilon}^{\omega}$  of analytic dynamics leaving invariant normally hyperbolic, periodic circles at which they are Diophantine rotation.

Then, a proof of the following problem would imply the local density of fast growth of the number of periodic points among analytic maps (for the inductive topology) by using Corollary 4.11 and then Grauert and Cartan B theorems.

Problem 4.12. Let  $f \in C^{\omega}(M, M)$  and let  $C$  be a  $C^{\infty}$ - circle included in  $M$  at which  $f$  is normally hyperbolic and such that the rotation number of  $f|_{C}$  is Diophantine. Show that  $C$  is analytic.

# 4.2. Theorem B

The proof of this Theorem B has a similar structure as the one of Theorem A, using Theorems 1.9 and 1.11 instead of Theorem 1.8 and  $C^{r}$ -  $\lambda$ - parablenders instead of  $\lambda$ - blenders. However, the perturbations will be more tricky to perform.

Proof of Theorem B. Let us show the existence of a locally dense subset  $\widehat{D}$  satisfying the assumptions of Theorems 1.9 and 1.11, and which is formed by families of diffeomorphisms when  $n = \dim M \geq 3$ .

Let  $\mathcal{B}_{r}^{\lambda}$  and  $(g_{p}^{\ell})_{\ell \in \mathcal{B}_{r}^{\lambda}}$  be as in 2.13 for every  $p \in B_{k}$ . Let

$$
g_{p}^{\ell}: x \longmapsto \frac{3}{2} \frac{x}{x + 1}
$$

for every  $p \in B_{k}$ . We consider these maps as acting on the compactification  $P^{1}(\mathbb{R})$  of  $\mathbb{R}$ . Let

$$
\mathcal{A} = \mathcal{B}_{r}^{\lambda} \cup \{\ell \}
$$

for a symbol  $\ell$  . By Proposition 3.8, for any  $\infty >r\geq 1$  , there is a  $C^{\infty}$  - embedding  $j$  of  $\Sigma \times$ $P^{1}(\mathbb{R})$  into the manifold  $P^{1}(\mathbb{R})\times (- 1,1)^{n - 1}\subset M$  and a  $C^{\infty}$  - family  $(f_{p})_{p\in B_{k}}$  of  $C^{\infty}$  - selfmaps  $f_{p}$  of  $M$  (which are diffeomorphisms if  $n\geq 3$  ) which are  $(r + 2)$  - normally expanding (or hyperbolic if  $n\geq 3$  ) at  $\mathcal{L}\coloneqq j(\Sigma \times P^{1}(\mathbb{R}))$  and such that  $g_{p} = j^{- 1}\circ f_{p}\circ j$  is the canonical map of  $\operatorname {End}_{\sigma}^{\infty}(\Sigma \times P^{1}(\mathbb{R}))$  associated with  $(g_{p}^{\mathcal{A}})_{\sigma \in \mathcal{A}}$

Let  $\hat{\mathcal{M}}$  be a small  $C^r$  - open neighborhood of  $(f_{p})_{p}$  intersected with the subset of  $C^{\infty}$  families. Given  $(\tilde{f}_p)_p\in \hat{\mathcal{M}}$  , let  $(\tilde{j}_p)_p$  be the family of embeddings given by Corollary 3.7 and let  $\tilde{g}_p\coloneqq \tilde{j}_p^{- 1}\circ \tilde{f}_p\circ \tilde{j}_p\in \mathrm{End}_{\sigma}^r (\Sigma \times P^1 (\mathbb{R}))$  and  $\hat{\mathcal{L}}_p\coloneqq \tilde{j}_p(\Sigma \times P^1 (\mathbb{R}))$  . The assumptions of Theorem 1.9 are implied by the following shown below.

CLAIM 4.13. There is a neighborhood  $B_{k}^{\prime}$  of  $0\in B_{k}$  such that, for all  $\eta >0$  and all  $(\tilde{f}_p)_p\in \hat{\mathcal{M}}$  , there is  $\eta^{\prime} > 0$  satisfying the following property. For every  $p_0\in B_k^{\prime}$  , there exists  $m\geq 1$  , a  $2m$  - periodic  $\mathcal{S}\in \Sigma$  and  $(\tilde{f}_p)_p\in \hat{\mathcal{M}}$  which is  $C^r$  -  $\eta$  - close to  $(\mathring{f}_p)_p$  , satisfies  $\tilde{f}_p = \mathring{f}_p$  for every  $p\notin ([- \eta ',\eta ']^k +p_0)$  , and such that, for every  $p\in \left[- \frac{2}{3}\eta ',\frac{2}{3}\eta '\right]^k +p_0$  , the restriction  $\tilde{f}_p^{2m}|_{\tilde{j}_p(\{\mathcal{J}\} \times P^1 (\mathbb{R}))}$  displays a parabolic point depending continuously on  $p$  and if  $r\geq 2$  this circle diffeomoprhism is parabolic.

For every  $\underline{n}_0\in \{0,1\} ^k$  and  $\eta >0$  , let  $\eta^{\prime} > 0$  and let  $(\tilde{f}_p)_p$  be the family whose restriction to  $[- \eta^{\prime},\eta^{\prime}]^{k} + p_{0}$  , for  $p_0$  in the finite set  $\{\eta^{\prime}\underline{n}_{0} + 2\eta^{\prime}\underline{n};\underline{n}\in \mathbb{Z}^{k}\} \cap B_{k}^{\prime}$  , is given by the above claim applied to  $(\mathring{f}_p)_p$  . Note that  $(\tilde{f}_p)_p$  is of class  $C^r$  and  $\eta$  - distant from  $(\mathring{f}_p)_p$  Furthermore it satisfies the following property:

$(\mathcal{P}(\underline{n}_0))$  For every  $\underline{n}\in \mathbb{Z}^{k}$  , there exists a  $2m$  - periodic point  $\mathcal{S}(n)\in \Sigma$  such that, for

$$
\begin{array}{r}p\in \big\{\eta '(underline{n}_0 + 2\underline{n}) + \big(-\frac{2}{3}\eta ',\frac{2}{3}\eta '\big)^k\big\} \cap B_k', \end{array}
$$

the restriction of  $\tilde{f}_p^{2m}$  to the fiber  $\tilde{j}_p(\{\mathcal{J}(\underline{n})\} \times P^1 (\mathbb{R}))$  displays a parabolic point depending continuously on  $p$  and if  $r\geq 2$  this circle diffeomorphism is parabolic.

Now, assume we embedded  $2^{k} = \mathrm{Card}\{0,1\}^{k}$  such normally hyperbolic fibrations at different places of  $M$  and label each by distinct numbers  $n_0\in \{0,1\} ^k$  . Then, we apply Claim 4.13 to each of these fibrations. This provides  $2^{k}$  different perturbations at uniformly distant subsets of  $M$  . Thus, there is a  $C^r$  - perturbation of the family of dynamics on the whole phase space whose restriction to the normally hyperbolic fibration indexed by  $\underline{n}_0$  satisfies  $\mathcal{P}(\underline{n}_0)$  , for every  $\underline{n}_0\in \{0,1\} ^k$  . As

$$
\bigcup_{\substack{n_0\in\{0,1\}^k,\underline{n}\in\mathbb{Z}^k}}\Bigl\{\eta '(n_0+2\underline{n})+\Bigl(-\frac{2}{3}\eta ',\frac{2}{3}\eta '\Bigr)^k\Bigr\}=\bigcup_{\underline{n}\in\mathbb{Z}^k}\Bigl\{\eta '\underline{n}+\Bigl(-\frac{2}{3}\eta ',\frac{2}{3}\eta '\Bigr)^k\Bigr\}=\bigcup_{\underline{n}\in\mathbb{Z}^k}\Bigl\{\eta '\underline{n}+\Bigl(-\frac{2}{3}\eta ',\frac{2}{3}\eta '\Bigr)^k\Bigr\}=\bigcup_{\underline{n}\in\{\underline{n}\}}
$$

we have shown the existence of a  $C^r$  - locally dense set  $\hat{D}_0$  of smooth families  $(\tilde{f}_p)_{p\in B_k'}$  satisfying the assumption of Theorem 1.9 with  $B_{k}^{\prime}$  instead of  $B_{k}$  . To get  $B_{k}$  instead of  $B_{k}^{\prime}$  , we regard  $\hat{D}\coloneqq \{(\tilde{f}_{\tau \cdot p})_{p\in B_k}\colon (\tilde{f}_p)_{p\in B_k}\in \hat{D}_0\}$  , with  $\tau >0$  such that  $B_{k}^{\prime}\supset \tau \cdot B_{k}$

Proof of Claim 4.13. First recall that we may assume that  $M = P^{1}(\mathbb{R}) \times (- 1,1)^{n - 1}$ . Also, we have the following.

FACT 4.14. Up to a  $C^{r + 1}$ - family of coordinates change close to the identity, we may assume that for any  $p \in B_k$ ,  $\tilde{f}_p(\Sigma \times \{0\}) \subset \{0\} \times (- 1,1)^{n - 1}$ , and if the 0 letter of  $\mathcal{J} \in \Sigma$  is  $\mathcal{C}$ , then the map  $\tilde{g}_p^{\mathcal{J}}$  fixes zero.

Proof. Let  $R_{p}$  be the source of the fiber of  $\tilde{\mathcal{L}}_{p}$  based at  $\epsilon^{\infty}$  . Using a coordinate change close to the identity, we may assume that it is in  $\{0\} \times (- 1,1)^{n - 1}$  . Also, its strong unstable manifold  $W_{\mathrm{loc}}^{\mathrm{w}}(R_p,\tilde{f}_p)$  is of class  $C^{r + 1}$  and depends  $C^{r + 1}$  on  $p$  . By Remark 3.10, we may assume it 1- dimensional and that the local strong stable manifold of its points form a  $C^{r + 1}$  submanifold  $N_{p}$  which depends  $C^{r + 1}$  on the parameter  $p$  . This family of submanifolds is  $C^{r}$  close to the constant family  $\{0\} \times U$  for an open subset  $U$  of  $(- 1,1)^{d}$  and intersects transversally each fiber of  $\tilde{\mathcal{L}}_{p}$  at a point close to zero. Moreover, it is locally invariant:  $N_{p}\cap \tilde{f}_{p}^{- 1}(N_{p})$  is an open set of  $N_{p}$

We achieve the proof using a coordinate change  $C^{r + 1}$ - close to the identity of  $M$  sending  $N_{p}$  into  $\{0\} \times (- 1,1)^{n - 1}$  and changing the coordinate of the fibers so that  $N_{p}$  intersects them at zero.

Similarly to the proof of Theorem A, let  $\mathcal{P}_m$  be the set of  $2m$ - periodic points of  $\Sigma$  whose  $\mathcal{A}$ - spelling is of the form  $\mathcal{A} = (\ell_{m},\ell^{m})^{\infty}$ ; its letters at the positions  $0,\ldots ,m - 1$  form a word  $\ell_{m} \in (\mathcal{B}_{r}^{\lambda})^{m}$ , and its  $m$  next letters are  $\ell$ . Then, we denote

$$
\tilde{g}_{p}^{\ell_{m}} \coloneqq \tilde{g}_{p}^{\ell^{m - 1}} \circ \ldots \circ \tilde{g}_{p}^{\ell^{0}} \text{and} \tilde{g}_{p}^{\ell^{m}} \coloneqq \tilde{g}_{p}^{\ell^{2m - 1}} \circ \ldots \circ \tilde{g}_{p}^{\ell^{m}} \text{with} \mathcal{J}^{j} \coloneqq \sigma^{j}(\mathcal{J}) \text{for every} j \geqslant 0. \tag{4.4}
$$

Note that, when  $(\tilde{g}_{p})_{p} = (g_{p})_{p}$ , we have  $\tilde{g}_{p}^{\ell^{m}} = (g_{p}^{\ell})^{m}$  for every  $p \in B_k$  and  $\tilde{g}_{p}^{\ell_{m}} = g_{p}^{\ell_{m}}$ , where  $g_{p}^{\ell_{m}}$  is the element of the semi- group spanned by  $(g_{p}^{\ell})_{\ell \in \mathcal{B}_{p}^{2}}$ . Using Fact 4.14, we have  $\tilde{g}_{p}^{\ell^{m}}(0) = 0$ . Let

$$
\ell_{m}) = \tilde{g}_{p}^{\ell^{m}}(0),\quad \tilde{\lambda}_{p}(\ell_{m}) = \frac{1}{m}\log |D_{0}\tilde{g}_{p}^{\ell_{m}}| \quad \text{and} \quad \tilde{\lambda}_{p}(\ell^{m}) = \frac{1}{m}\log |D_{0}\tilde{g}_{p}^{\ell_{m}}|.
$$

We notice that  $\tilde{x}_{p}(\ell_{m})$  belongs to  $(- 2,2)$ , also  $\tilde{\lambda}_{p}(\ell^{m}) \approx \log \frac{2}{3}$  and  $\tilde{\lambda}_{p}(\ell_{m}) < 0$ . Note that if  $\tilde{x}_{p}(\ell_{m}) = 0$ , then it is the unique point of  $\tilde{g}_{p}^{\ell^{m}}$  in  $(- 2,2)$ . The proof of the following is the same as the one of Proposition 4.2.

PROPOSITION 4.15. Let  $r \geq 2$ . For  $\hat{\mathcal{M}}$  and  $B_{k}^{\prime}$  small enough, for every  $(\ell_{m} \cdot \ell^{m})^{\infty} \in \mathcal{P}_{m}$  with  $m$  large, for every  $(\tilde{f}_{p})_{p} \in \hat{\mathcal{M}}$  and  $p \in B_{k}^{\prime}$ , the map  $\tilde{h}_{p} \coloneqq \tilde{g}_{p}^{\ell^{m}} \circ \tilde{g}_{p}^{\ell_{m}}$  is parabolic if

$$
\tilde{x}_{p}(\ell_{m}) = 0 \quad \text{and} \quad \tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}) = 0.
$$

Hence, Claim 4.13 is a consequence of the next claim for every  $r \geq 1$ .

CLAIM 4.16. For  $\hat{\mathcal{M}}$  and  $B_{k}^{\prime}$  small enough, for all  $\eta >0$  and  $(\mathring{f}_{p})_{p}\in\hat{\mathcal{M}}$  , there exists  $\eta^{\prime} > 0$  such that the following holds.

For every  $p_0\in B_k^{\prime}$  , there exists  $(\mathring{f}_{p})_{p}\in\hat{\mathcal{M}}$  which is  $C^r$ $\eta$  - close to  $(\mathring{f}_{p})_{p}$  , satisfies  $\mathring{f}_{p} = \mathring{f}_{p}$  for all  $p\notin \left([- \eta^{\prime},\eta^{\prime}]^{k} + p_{0}\right)$  , and there exists  $(\ell_{m}\cdot \ell^{m})^{\infty}\in \mathcal{P}_{m}$  with  $m$  large at which

$$
\tilde{x}_{p}(\ell_{m}) = 0\quad a n d\quad \tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}) = 0\quad f o r a l l p\in \left[-\frac{2}{3}\eta^{\prime},\frac{2}{3}\eta^{\prime}\right]^{k} + p_{0}.
$$

Proof. The following applies the  $C^r$ $\lambda$  - parablender property; it assumes  $\hat{\mathcal{M}}$  and  $B_{k}^{\prime}$  small enough.

LEMMA 4.17. For every  $p_0\in B_k^{\prime}$  and  $(\mathring{f}_{p})_{p}\in\hat{\mathcal{M}}$  , when m is large, there exists

$$
(\ell_{m}\cdot \ell^{m})^{\infty}\in \mathcal{P}_{m}
$$

such that  $J^{r}(\tilde{x}_{p}(\ell_{m}))_{p}$  is small and  $J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell^{m}))_{p} + J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell_{m}))_{p}$  is small.

Proof. Assume that  $\Sigma = \mathcal{A}^{\mathbb{N}}$  .We recall that  $\ell^{\infty}\in \Sigma$  denotes the point whose  $\mathcal{A}$  spelling is formed uniquely of the letter  $\ell$  . We recall that zero is the repulsive fixed point of  $g_{p}^{\infty}$  , let  $\tilde{\lambda}_{p}(\ell^{\infty})$  be its Lyapunov exponent. For  $\hat{\mathcal{M}}$  and  $B_{k}^{\prime}$  small enough, we have that  $(- \tilde{\lambda}_{p}(\ell^{\infty}))_{p}$  is  $C^{r - 1}$  - close to  $\left(\log {\frac{2}{3}}\right)_{p}$  . Then, by Example 3.20, the jet

$$
(\ell^{\infty},0, - J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell^{\infty}))_{p})
$$

is included in the Lyapunov fibration of the unstable set of the  $\lambda$ $C^r$  - parablender equal to the continuation of  $(\mathcal{B}_{r}^{\lambda})^{\mathbb{N}}\times [- 1,1]$  . Thus, with  $\sum^{\prime}$  the space of  $\sigma$  - preorbits with 0- coordinate in  $\mathcal{B}_{r}^{\lambda}$  (see Example 3.20), there is  $\underline{{\mathcal{J}}} = (\mathcal{J}_{- m})_{m\geqslant 1}\in \overleftarrow{\Sigma}^{\prime}$  such that, with  $v_{- m} = (\mathcal{J}_{- m},0)$

$$
\lim_{m\to \infty}J_{p_{0}}^{r}\big(g_{p}^{m}(v_{-m})\big)_{p} = (c^{\infty},0)
$$

and

$$
\lim_{m\to \infty}J_{p_{0}}^{r - 1}\bigg(\frac{1}{m}\log |\partial_{x}g_{p}^{m}(v_{-m})|\bigg)_{p} = -J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell^{\infty}))_{p}.
$$

Note that each  $\mathcal{J}_{- m}$  is the concatenation of  $\ell_{m}^{\prime}\in \mathcal{B}_{r}^{\lambda}$  with  $\ell^{\infty}$  . By Lemma 4.7 (whose statement and argument are still valid in the present setting), this implies

$$
\lim_{m\to \infty}J_{p_{0}}^{r}(\tilde{x}_{p}(\ell_{m}))_{p}\mathop{=}_{m\to \infty}0\quad \mathrm{and}\quad \lim_{m\to \infty}J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell^{m}))_{p} + J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell_{m}))_{p} = 0
$$

If  $\Sigma = \mathcal{A}^{\mathbb{Z}}$  , we observe that the statement of the lemma is invariant by the  $C^r$  - conjugacy of  $P^{1}(\mathbb{R})\times \Sigma$  given by Proposition 3.11 which leaves invariant zero by Fact 4.14. So, we can use the case  $\Sigma = \mathcal{A}^{\mathbb{N}}$  to get the case  $\Sigma = \mathcal{A}^{\mathbb{Z}}$  , as we did in Claim 4.3.

Now, we fix  $m$  large and  $\ell_{m}$  given by the previous lemma. The idea is to perturb the dynamics so that  $\tilde{x}_{p}(\ell_{m}) = 0$  and  $\tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}) = 0$ . Contrarily to the proof of Claim 4.3, it is difficult to handle such a perturbation using new parameters, since we have only  $C^{r - 1}$ - bounds on the family  $(\tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}))_{p}$ . So, the perturbation technique is going to be extrinsic.

Recall that  $\mathcal{J}\coloneqq (\ell_{m}\cdot \ell^{m})^{\infty}$  and  $\mathcal{J}^{j}\coloneqq \sigma^{j}(\mathcal{J})$ . Note that  $\mathcal{J}^{m}\coloneqq (\ell^{m}\cdot \ell_{m})^{\infty}$ . Let

$$
S_{p}\coloneqq \tilde{j}_{p}(\mathcal{J}^{m},0)\quad \mathrm{and}\quad S_{p}^{\prime} = \tilde{j}_{p}(\mathcal{J}^{m},\tilde{x}_{p}(\ell_{m})).
$$

Observe that  $\tilde{f}_{p}^{2m}(S_{p}) = S_{p}^{\prime}$  and  $J_{p_{0}}^{r}(S_{p}^{\prime})_{p}$  is close to  $J_{p_{0}}^{r}(S_{p})_{p}$ . Indeed,  $\tilde{f}_{p}^{m}(S_{p}) = \tilde{j}_{p}(\mathcal{J},0)$  and so  $\tilde{f}_{p}^{2m}(S_{p}) = \tilde{j}_{p}(\mathcal{J}^{m},\tilde{x}_{p}(\ell_{m})) = S_{p}^{\prime}$ . As  $J_{p_{0}}^{r}(\tilde{x}_{p}(\ell_{m}))_{p}$  is small, it comes that  $J_{p_{0}}^{r}(S_{p}^{\prime})_{p}$  is close to  $J_{p_{0}}^{r}(S_{p})_{p}$ . The following lemma makes a perturbation of  $(\tilde{f}_{p})_{p}$  so that  $S_{p}^{\prime} = S_{p}$  when  $p$  is uniformly close to  $p_{0}$ . Then,  $S_{p}$  will be a  $2m$ - periodic point or equivalently  $\tilde{x}_{p}(\ell_{m}) = 0$  as sought by the first equality of Claim 4.16.

LEMMA 4.18. There exists  $\eta^{\prime} > 0$  which is independent of  $p_{0}\in B_{k}^{\prime}$  such that, when  $m$  is large, there is an  $\frac{1}{2}\eta$ -  $C^{r}$ - perturbation of  $(\tilde{f}_{p})_{p}$  which is supported by  $p\in p_{0} + [- \eta^{\prime},\eta^{\prime}]^{k}$  and such that, for every  $p\in p_{0} + [- \frac{2}{3}\eta^{\prime},\frac{2}{3}\eta^{\prime}]^{k}$ , the points  $S_{p}^{\prime}$  and  $S_{p}$  coincide. In other words,  $\tilde{x}_{p}(\ell_{m}) = 0$ . Moreover, the families  $(\tilde{\lambda}_{p}(\ell^{m}))_{p}$  and  $(\tilde{\lambda}_{p}(\ell_{m}))_{p}$  are unchanged.

Proof. It suffices to notice that the  $\hat{\mathcal{L}}_{p}$ - fiber of the point  $\tilde{f}_{p}^{2m - 1}(S_{p})$  is isolated with respect to the fibers of the other points  $(\tilde{f}_{p}^{k}(S_{p}))_{0\leqslant k\leqslant 2m - 2}$ . Indeed, the letters at the 0 and 1 position of  $\mathcal{J}^{m - 1}$  are in  $\mathcal{B}_{r}^{\lambda}$  and  $\{\ell \}$ , respectively, while it is not the case for the other  $\mathcal{J}^{k}$ . Thus, we can use a translation along this fiber so that  $S_{p}^{\prime}$  is sent to  $S_{p}$ , and extends this translation at a neighborhood of this fiber (using a  $C^{r}$ - tubular neighborhood). Then, using a bump function we perform a local perturbation of  $(\tilde{f}_{p})_{p}$  so that this perturbation is supported by the product of a small neighborhood of  $\tilde{f}_{p_{0}}^{2m - 2}(S_{p_{0}})$  with  $p_{0} + [- \eta^{\prime},\eta^{\prime}]^{k}$ , while  $\tilde{f}_{p}^{2m - 1}(S_{p})$  is sent to  $S_{p}$  for every  $p\in p_{0} + [- \frac{2}{3}\eta^{\prime},\frac{2}{3}\eta^{\prime}]^{k}$ . Note that such perturbation does not change the fiber of the orbit of  $\mathcal{J}$ . Furthermore, as  $J_{p_{0}}^{r}(S_{p}^{\prime})_{p}$  is close to  $J_{p_{0}}^{r}(S_{p})_{p}$ , the family of translation is  $C^{r}$ - small, and so is its product with the bump function when  $\eta^{\prime}$  is sufficiently small.

Actually  $\eta^{\prime}$  does not depend on  $m$  large nor  $p_{0}$ . Indeed,  $(S_{p})_{p\in B_{k}}$  and  $(\tilde{f}_{p}^{m}(S_{p}))_{p\in B_{k}}$  belongs to the set of  $C^{r}$ - families  $(\tilde{j}_{p}(\mathcal{J}^{\prime},0))_{p\in B_{k}}$ . These depend continuously among  $\mathcal{J}^{\prime}$  in the compact set  $\Sigma$ . So, the modulus of continuity of their  $r$ th derivatives is uniform. The same occurs for the set of families  $(\tilde{f}_{p}^{j}(S_{p}))_{p\in B_{k}}$  among  $m\leqslant j\leqslant 2m$ , which is included in the set of fixed points of a compact families of fiber contractions. Thus, the moduli of continuity of the  $r$ th derivatives of  $(S_{p})_{p}$  and  $(S_{p}^{\prime})_{p}$  are bounded independently of  $p_{0}\in B_{k}^{\prime}$  and  $m$  large. This gives the sought property.

Now, it remains to perturb the dynamics to make the periodic point  $S_{p}$  semiparabolic (which is now equivalent to  $\tilde{\lambda}_{p}(\ell^{m}) + \tilde{\lambda}_{p}(\ell_{m}) = 0$ ). There are two difficulties. First, the perturbation should be done in many fibers, since we have to perturb the average central Lyapunov exponent: this must be done at many fibers. Secondly, this average Lyapunov exponent is only small in the  $C^{r - 1}$ - topology while we have to handle a  $C^{r}$ - perturbation. However, we have the following.

LEMMA 4.19. There is a Lipschitz map which sends  $C^{r - 1}$  families  $\lambda = (\lambda_{p})_{p\in B_{k}}$  of numbers  $\lambda_{p}$  to  $C^{r}$ - families  $(h_{p}^{\lambda})_{p\in B_{k}}$  of self- maps  $h_{p}^{\lambda}$  of  $P^{1}(\mathbb{R})$  such that  $h_{p}^{0}$  is the identity and, for every  $\lambda$ ,

$$
h_{p}^{\lambda}(0) = 0\quad a n d\quad \log |D_{0}h_{p}^{\lambda}| = \lambda_{p}.
$$

Proof. Given a point  $(0,p_{1})\in \{0\} \times B_{k}$ , the following is a  $C^{r}$ - jet of a real function on  $\mathbb{R}\times B_{k}$ :

$$
J_{0,p_{1}}^{r}u(\lambda)(x,p) = x\cdot \sum_{|j|\leqslant r - 1}\frac{1}{(j + 1)!}\partial_{p}^{j}(\exp \lambda_{p_{1}})(p - p_{1})^{j + 1} - x.
$$

By Whitney extension Theorem [23, Theorem 2.3.10], there is a Lipshitz, linear operator  $u$  which sends  $\lambda$  to a function  $u(\lambda)$  from  $P^{1}(\mathbb{R})\times B_{k}$  into  $\mathbb{R}$ , such that its  $C^{r}$ - jets at  $\{0\} \times B_{k}$  matches with the above expression. Then, using a bump function, we may assume that  $u(\lambda)$  is compactly supported. Then, put

$$
h_{p}^{\lambda}\colon x\in P^{1}(\mathbb{R})\longmapsto x + u(\lambda)(x,p)\in P^{1}(\mathbb{R}).
$$

Recall that we assumed that  $M = P^{1}(\mathbb{R})\times (- 1,1)^{n - 1}$  and that the fibers of  $\tilde{\mathcal{L}}_{p}$  are transverse to the fibers of  $P^{1}(\mathbb{R})\times (- 1,1)^{n - 1}\to P^{1}(\mathbb{R})$ . This does not change the limit of

$$
J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell^{m}))_{p} + J_{p_{0}}^{r - 1}(\tilde{\lambda}_{p}(\ell_{m}))_{p}
$$

when  $m\to \infty$  to assume that the norm on the tangent space of  $\tilde{\mathcal{L}}_{p}$  is induced by the first coordinate projection

$$
P^{1}(\mathbb{R})\times (-1,1)^{n - 1}\longrightarrow P^{1}(\mathbb{R}).
$$

Now we use the latter lemma, with  $\lambda = (- 2\tilde{\lambda}_{p}(\ell_{m}) - 2\tilde{\lambda}_{p}(\ell^{m}))_{p}$ . This provides a family of maps  $h_{p}^{\lambda}\colon P^{1}(\mathbb{R})\to P^{1}(\mathbb{R})$  fixing zero and having the jet defined by  $\lambda$ . Let  $(H_{p}^{\lambda})_{p}$  be a  $C^{r}$ - family of maps of  $M$  which leaves invariant the trivial fibration

$$
P^{1}(\mathbb{R})\times (-1,1)^{n - 1}\longrightarrow (-1,1)^{n - 1},
$$

which is  $C^{r}$ - close to the identity, coincides with the identity nearby any fiber with 0- letter in  $\mathcal{B}_{r}^{\lambda}$  and equal to  $h_{p}^{\lambda}$  nearby any other fibers. Then,  $S_{p}$  is still a  $2m$ - periodic point

for  $H_{p}^{\lambda} \circ \breve{f}_{p}$ . Also, half of points in the orbit of  $S_{p}$  have their derivatives along the fibration multiplied by  $\exp (2\lambda_{p})$ , while the others are unchanged. Thus,  $S_{p}$  is semi- parabolic for  $H_{p}^{\lambda} \circ \breve{f}_{p}$ . Note that, after this perturbation, the fibration might have changed. However, the  $2m$ - periodic point  $S_{p}$  shadows the normally hyperbolic,  $2m$ - periodic fiber of  $\mathcal{J}^{m}$  and so must lie in it.  $\square$

# 5. Perturbation of families of parabolic circle maps to constant rotations

This section is devoted to the proof of Theorem 1.4. Let  $k \in \mathbb{N}$  and let  $B \subset \mathbb{R}^{k}$  be an open subset. Let  $(g_{p})_{p \in B}$  be a  $C^{\infty}$ - family of circle diffeomorphisms so that, for every  $p \in B$ , the map  $g_{p}$  is parabolic. Given any  $B' \Subset B$ , we want to find a  $C^{\infty}$ - perturbation  $(\tilde{g}_{p})_{p \in B}$  of  $(g_{p})_{p \in B}$  such that  $\tilde{g}_{p}$  displays a Diophantine rotation number which does not depend on  $p \in B'$ .

We shall work with the coordinates given by a 1- point compactification  $P^{1}(\mathbb{R})$  of  $\mathbb{R}$ . Hence, given  $a < b \in \mathbb{R}$ , we will denote by  $(a, b)$  the segment of  $\mathbb{R} \subset P^{1}(\mathbb{R})$ , and by  $(b, \infty , a)$  the arc of  $P^{1}(\mathbb{R})$  containing  $\infty$  and with endpoints  $\{a, b\}$ .

Sketch of proof. The proof of the theorem is done by the following steps:

(1) First we show that in a  $C^{\infty}$  -family of coordinates, we may assume that, for every  $p\in B$  (a) the map  $g_{p}$  fixes zero, satisfies  $D^{2}g_{p}(0) = 2$  and sends  $\{\textstyle {\frac{1}{2}},1, - 1\}$  to  $\{1, - 1, - \textstyle {\frac{1}{2}}\}$  (b) up to a  $C^{\infty}$  perturbation of  $(g_{p})_{p}$  , the restriction of  $g_{p}$  to  $\left[-1,\frac{1}{2}\right]$  coincides with the time-1 flow of a smooth vector field  $X_{p}$  on  $[-1,1]$  depending  $C^{\infty}$  on  $p$  
(2) We look at a family of perturbations  $(g_{p\eta})_p$  for  $\eta$  small defined by  $g_{p\eta}$  is equal to  $g_{p}$  on  $\textstyle{\left(\frac{1}{2},\infty , - 1\right)}$ $g_{p\eta}$  coincides on  $\left[-1,\frac{1}{2}\right]$  with the time-1 map of the flow of the vector field  $X_{p}+$ $\rho \cdot \eta^{2}$  for a fixed  $\rho \in C^{\infty}(\mathbb{R},[0,1])$  supported by  $\left(-\textstyle {\frac{1}{2}},\textstyle {\frac{1}{2}}\right)$  and such that  $\rho (0) = 1$

Then, we show that in some coordinates (given by the two canonical extensions of  $X_{p}$  over  $(1, \infty , - 1)$ ) the first return map  $G_{p\eta}$  of  $g_{p\eta}$  in  $(1, \infty , - 1)$  is of the form  $G_{p0} + \omega_{p}^{+}(\eta)$ , with  $(p, \eta) \mapsto \omega_{p}^{+}(\eta)$  of class  $C^{\infty}$ .

(3) We show the existence of a  $C^{\infty}$ -family  $(\Omega_{p})_{p}$  of functions  $\Omega_{p} \in C^{\infty}([0, \infty), \mathbb{R})$  such that  $\Omega_{p}(0) = 1 / \pi$  and  $\omega_{p}^{+}(\eta) = \Omega_{p}(\eta) / \eta$  mod 1 for every  $p$ ; using an integral formula on  $\omega_{p}^{+}(\eta)$ .

(4) We use the following KAM's theorem of Herman-Yoccoz.

THEOREM 5.1. (Herman- Yoccoz) For every  $\beta \in \mathbb{R}$  Diophantine, let  $V_{\beta}$  be the set of circle diffeomorphisms in  $\mathrm{Diff}^{\infty}(\mathbb{R} / \mathbb{Z})$  whose rotation number is  $\beta$ . Then,  $V_{\beta}$  is a smooth submanifold of codimension 1. Moreover, for every  $f \in V_{\beta}$ , the family  $(f + b)_{b \in \mathbb{R}}$  is transverse to  $V_{\beta}$  at  $b = 0$ .

Proof. By Yoccoz' Theorem 1.1, we may assume that  $f$  is the rotation of angle  $\beta$ . Then, the theorem is stated in [14, Remark 3.1.3].  $\square$

Then, given a Diophantine number  $\beta$ , we can define implicitly an arbitrarily  $C^{\infty}$ - small function  $p \mapsto \eta (p)$  (for the compact- open topology), so that the return map  $G_{p\eta (p)}$  displays the rotation number  $\beta$  for every  $p \in B'$ . This implies that the rotation number of  $g_{p\eta (p)}$  is of the form  $1 / (N + \beta)$ , and so is Diophantine as well. In other words, with  $g_{p}^{\prime} \coloneqq g_{p\eta (p)}$ , the family  $(g_{p}^{\prime})_{p}$  satisfies the sought properties.  $\square$

Step 1: Setting. (a) Let  $x_{p} \in P^{1}(\mathbb{R})$  be the fixed point of  $g_{p}$  for  $p \in B$ . As the map  $g_{p}$  is parabolic,  $\partial_{x}g_{p}(x_{p}) = 1$  and  $\partial_{x}^{2}g_{p}(x_{p}) \neq 0$ . Hence,  $x_{p}$  can be defined (locally) as the zero of

$$
(x,p)\longmapsto \partial_{x}g_{p}(x) - 1.
$$

Hence, by the implicit function theorem, the map  $p \mapsto x_{p}$  is of class  $C^{\infty}$ . Thus, by a smooth coordinate change, we may assume that  $x_{p} = 0$  for every  $p \in B$ . Then, we can conjugate the dynamics by the Moebius function

$$
x \longmapsto \frac{2 \cdot x}{D^{2}g_{p}(x_{p})}
$$

for every  $p \in B$ , so that for every  $p \in B$  we have

$$
g_{p}(0) = 0, \quad Dg_{p}(0) = 1 \quad \text{and} \quad D^{2}g_{p}(0) = 2.
$$

Now, we conjugate  $g_{p}$  by a smooth family of diffeomorphisms, equal to the identity on a neighborhood of zero and sending  $\frac{1}{2}$ ,  $g_{p}\left(\frac{1}{2}\right)$ ,  $g_{p}^{2}\left(\frac{1}{2}\right)$  and  $g_{p}^{3}\left(\frac{1}{2}\right)$  to  $\frac{1}{2}$ ,  $1$ ,  $- 1$  and  $- \frac{1}{2}$ , respectively (see Figure 1).

(b) Let  $d \geq 2$  and

$$
\mathfrak{G}_{d} = \left\{\sum_{j = 2}^{r} \frac{g_{j}}{j!} x^{j}: (g_{j})_{j = 2}^{d} \in \mathbb{R}^{d - 1} \right\} .
$$

Given  $\mathfrak{X} \in \mathfrak{G}_{d}$ , let  $\phi_{\mathfrak{X}}$  be the time- 1 flow of the vector field  $x + \mathfrak{X}(x)$ . Let  $J_{0}^{d} \phi_{\mathfrak{X}}$  be the  $C^{d}$ - jet of  $\phi_{\mathfrak{X}}$ :

$$
J_{0}^{d} \phi_{\mathfrak{X}} = \sum_{j = 0}^{d} \frac{\partial^{j} \phi_{\mathfrak{X}}}{j!} x^{j} = x + \sum_{i = 2}^{d} \frac{\partial^{j} \phi_{\mathfrak{X}}}{j!} x^{j}.
$$

![](https://cdn-mineru.openxlab.org.cn/extract/47a40ade-36a5-4e27-a4cb-43d85c4e296b/51ee8719da778388f076b07544d2838fd4bc580c559c6ad6984763e495f3decd.jpg)  
Figure 1.

In other words,  $J_{0}^{d}\phi_{\mathfrak{X}}$  belongs to the space  $G_{d}$  of  $C^{d}$  - jets of parabolic maps at zero:

$$
G_{d} = \left\{x + \sum_{j = 2}^{d}\frac{p_{j}}{j!} x^{j} + o(x^{d}):(p_{j})_{j = 2}^{d}\in \mathbb{R}^{d - 1}\right\} .
$$

Proposition 5.2. The map  $\mathfrak{X}\in \mathfrak{G}_{d}\mapsto \phi_{\mathfrak{X}}\in C^{\infty}(\mathbb{R},\mathbb{R})$  is smooth. Moreover, the following map is a diffeomorphism onto its image:

$$
\Psi \colon \mathfrak{X}\in \mathfrak{G}_{d}\longmapsto J_{0}^{d}\phi_{\mathfrak{X}}\in G_{d}.
$$

Proof. The first statement of this proposition is a simple consequence of the CauchyLipschitz theorem. The second part of the proposition involves the Lie group theory. Indeed, the  $C^{d}$  - jet space  $G_{d}$  endowed with the composition rules is a Lie group. Moreover, it satisfies the following.

Fact 5.3. The group  $G_{d}$  is connected, simply connected and nilpotent.

Proof. The group  $G_{d}$  is homeomorphic to  $\mathbb{R}^{d - 1}$  , and hence it is connected and simply connected. Let

$$
G_{d}^{(s)}\coloneqq \{\phi \in G_{d}\colon \phi (x) = x + O(x^{s + 2})\}
$$

for  $s\geqslant 0$  . A computation gives  $[G_{d},G_{d}^{(s)}]\subset G_{d}^{(s + 1)}$  . Since  $G_{d}^{(d + 1)}$  is trivial,  $G_{d}$  is nilpotent with rank  $\leq d - 1$

We notice that  $\mathfrak{G}_{d}$  is the Lie algebra of the group  $G_{d}$  . Moreover, the jet of  $\phi_{\mathfrak{X}}$  is the image by the exponential map exp of  $\mathfrak{X}\in \mathfrak{G}_{d}$  . Indeed, if  $\phi_{\mathfrak{X}}^{t} = \exp (t\cdot \mathfrak{X})$  and so  $\phi_{\mathfrak{X}} = \phi_{\mathfrak{X}}^{1}$  we have

$$
\phi_{\mathfrak{X}}^{t + \delta t} = \phi_{\mathfrak{X}}^{\delta t}\circ \phi_{\mathfrak{X}}^{t} = (\mathrm{id} + \delta t\cdot \mathfrak{X})\circ \phi_{\mathfrak{X}}^{t} + o(\delta t).
$$

Finally, we infer that for a simply connected and nilpotent Lie group, the exponential map is an analytic diffeomorphism from the Lie algebra onto the group; cf. [17, p. 13, Theorem 1.2.1].

COROLLARY 5.4. There exists a  $C^{\infty}$ - map  $p \mapsto X_p \in \mathfrak{G}_d$  such that

$$
J_{0}^{d}\phi_{X_{p}} = J_{0}^{d}g_{p}
$$

for every  $p$ .

Let us fix a bump function  $\rho$  equal to 1 on  $\left[- \frac{1}{4}, \frac{1}{4}\right]$  and with support in  $\left(- \frac{1}{2}, \frac{1}{2}\right)$ , and for  $\epsilon > 0$  small, put

$$
\tilde{g}_p \colon x \longmapsto \rho \left(\frac{x}{\epsilon}\right) \cdot \phi_{X_p}(x) + \left(1 - \rho \left(\frac{x}{\epsilon}\right)\right) \cdot g_p(x).
$$

LEMMA 5.5. For  $d$  large and then  $\epsilon > 0$  small, the family  $(\tilde{g}_p)_{p \in B}$  is  $C^{\infty}$ - close to  $(g_p)_{p \in B}$ .

Proof. We have

$$
g_p(x) - \tilde{g}_p(x) = \rho \left(\frac{x}{\epsilon}\right) \left(g_p(x) - \phi_{X_p}(x)\right).
$$

For every  $j \leq d$ , we notice that  $(p, x) \in B \times [- \epsilon , \epsilon ] \mapsto g_p(x) - \phi_{X_p}(x)$  has its  $j$ th derivative which is small with respect to  $\epsilon^{d - j}$ . On the other hand, the  $j$ th derivative of  $\rho (x / \epsilon)$  is dominated by  $\epsilon^{- j}$ . Hence, by Leibnitz formula, the  $C^d$ - norm of

$$
(p, x) \in B \times (-\epsilon , \epsilon) \longmapsto g_p(x) - \tilde{g}_p(x)
$$

is small when  $\epsilon$  is small.

Observe that  $(\tilde{g}_p)_{p \in B}$  satisfies condition (a), and is equal to the time- 1 map of the flow defined by  $X_p$  at the neighborhood of zero. Using the formula  $D\tilde{g}_p \circ X_p \circ \tilde{g}_p^{- 1} = X_p$ , we pull back  $X_p$  to extend it to  $[- 1, 0]$ , and we push forward to extend it on  $[0, 1]$ . This defines a smooth family of vector field on  $[- 1, 1]$  such that condition (b) holds true. Hence, we can suppose that, after perturbation,  $(g_p)_{p \in B}$  satisfies conditions (a) and (b), and furthermore we have the following.

CLAIM 5.6. We have  $X_p(x) = x^2 + O(x^3)$  for every  $p$ .

Proof. When  $x \to 0$ , we have that  $J_0^d g_p^2 (x) - J_0^d g_p(x)$  is equivalent to both

$$
\begin{array}{r}{\frac{1}{2} D^{2}g_{p}(0)x^{2} = x^{2}\quad \mathrm{and}\quad X_{p}(x).} \end{array}
$$

Step 2. Definition of  $(g_{p\eta})_{p,\eta}$  and uniform bound on its first return map. Recall that  $\rho$  is a bump function equal to 1 on  $\left(- \frac{1}{4},\frac{1}{4}\right)$  and with support in  $\left(- \frac{1}{2},\frac{1}{2}\right)$  . For  $\eta >0$  small, let

$$
X_{p\eta} \colon x \in [-1, 1] \longmapsto X_p(x) + \eta^2 \rho (x).
$$

We recall that, for  $x$  in  $[- 1,\frac{1}{2} ]$  the time- 1 map of the flow of  $X_{p}$  is well defined and equal to  $g_{p}$ . Also,  $g_{p}$  sends  $- 1$  to  $- \frac{1}{2}$  and  $\frac{1}{2}$  to  $1$ , and the images by the flow of  $X_{p}$  of these points during times in  $[0,1]$  are, respectively,  $[- 1, - \frac{1}{2} ]$  and  $[\frac{1}{2},1]$ . Thus, for  $\eta$ - small, the time- 1 map  $\phi_{p\eta}^{1}(x)$  of the flow is well defined on  $[- 1,\frac{1}{2} ]$  and coincides with  $g_{p}$  nearby  $\{- 1,\frac{1}{2}\}$ . This implies the following.

CLAIM 5.7. The following family  $(g_{p\eta})_{p,\eta}$  of  $C^{\infty}$ - dynamics  $g_{p\eta}$  is well defined and smooth:

$$
g_{p\eta}:x\longmapsto \left\{ \begin{array}{ll}\phi_{p\eta}^{1}(x), & \text{if} x\in [-1,\frac{1}{2} ],\\ g_{p}(x), & \text{if} x\in (\frac{1}{2},\infty , - 1). \end{array} \right.
$$

For  $\eta >0$ , let us study the first return map  $T_{p\eta}$  of  $g_{p\eta}$  into  $[1,\infty , - 1] = [1,\infty ,g_{p\eta}(1)]$ . To this aim, we shall work with two different possible extensions of  $X_{p}|_{[- 1,1]}$  on  $(1,\infty , - 1)$ . Let

$$
\left\{ \begin{array}{ll}X_{p}^{+}\coloneqq x\in [1,\infty , - 1)\mapsto Dg_{p}\circ X_{p}\circ g_{p}^{-1}(x),\\ X_{p}^{-}\coloneqq x\in (1,\infty , - 1]\mapsto Dg_{p}^{-1}\circ X_{p}\circ g_{p}(x). \end{array} \right.
$$

In general,  $X_{p}^{+}$  and  $X_{p}^{- }$  are different. As  $X_{p}|_{[- 1,1]}$  is equal to  $X_{p\eta}|_{[- 1, - 1 / 2]\cup [1 / 2,1]}$ , we have the following.

FACT 5.8. The vector field  $X_{p}^{+}$  extends smoothly  $X_{p\eta}|_{(- 1,1)}$  to one denoted by  $X_{p\eta}^{+}$  on  $P^{1}(\mathbb{R})\backslash \{- 1\}$ . Also,  $X_{p}^{- }$  extends smoothly  $X_{p\eta}$  to one denoted by  $X_{p\eta}^{- }$  on  $P^{1}(\mathbb{R})\backslash \{1\}$ .

We now study the first return map  $T_{p\eta}$  in  $(1,\infty , - 1]$  induced by  $g_{p\eta}$ . The idea is to glue the endpoints  $1$  and  $- 1 = g_{p\eta}(1)$  of this interval by the dynamics, so that the quotient  $(1,\infty , - 1] / \sim$  is a circle, and the action of  $T_{p\eta}$  on it enjoys nice bounds when  $\eta \rightarrow 0$ .

Let  $N = N(\eta)$  be the first return time of  $- 1$  into  $(1,\infty , - 1]$ , let

$$
\omega_{p}(\eta) = g_{p\eta}^{N}(-1)\in (1,\infty , - 1].
$$

As  $g_{p\eta}$  is orientation preserving, the point at the left of  $- 1$  (see Figure 2) are sent by  $g_{p}^{N}$  at the left of  $\omega_{p}(\eta)$  until they exit of  $[- 1,\infty ,1]$ . Let  $\alpha_{p}(\eta)\in [1,\infty , - 1]$  be the point sent by  $g_{p\eta}^{N}$  to  $1$ . Hence,

$$
T_{p\eta}(-1) = \omega_{p}(\eta)\quad \mathrm{and}\quad T_{p\eta}(\alpha_{p}(\eta))\sim 1.
$$

To bound  $T_{p\eta}$ , we consider the diffeomorphisms  $C_{p}^{+}$  and  $C_{p}^{- }$  from  $[0,1]$  onto  $[1,\infty , - 1]$  which with  $t\in [0,1]$  associate the image of  $1$  by the time  $t$  of the flow of  $X_{p}^{+}$  and  $X_{p}^{- }$ , respectively:

$$
C_{p}^{+}\colon [0,1]\to [1,\infty , - 1]\quad \mathrm{and}\quad C_{p}^{-}\colon [0,1]\to [1,\infty , - 1].
$$

![](https://cdn-mineru.openxlab.org.cn/extract/47a40ade-36a5-4e27-a4cb-43d85c4e296b/2ad62b4fe5b768220deb8cc1f06178d9d646b96a25c9fdabb8d7dbb7a2b23d7c.jpg)  
Figure 2. Notation for the parabolic renormalization.

Remark also that both  $C_{p}^{\pm}$  do not depend on  $\eta$ , since  $X_{p}^{\pm}$  does not depend on  $\eta$ .

Let  $T_{p\eta}^{- }\coloneqq (C_{p}^{- })^{- 1}\circ T_{p\eta}\circ C_{p}^{- }$  be the first return map  $T_{p\eta}$  seen in the coordinates  $C_{p}^{- }$ . Let  $\alpha_{p}^{\pm}(\eta)$  and  $\omega_{p}^{\pm}(\eta)$  be the preimages of  $\alpha_{p}(\eta)$  and  $\omega_{p}(\eta)$  by  $C_{p}^{\pm}$ . We observe that (see Figure 2)

$$
T_{p\eta}^{-}(1) = \omega_{p}^{-}(\eta)\quad \mathrm{and}\quad T_{p\eta}^{-}(\alpha_{p}^{-}(\eta)) = 0.
$$

We define the following coordinates change:

$$
\Phi_{p}\colon [0,1]\longmapsto (C_{p}^{-})^{-1}\circ C_{p}^{+}(t)\in [0,1].
$$

CLAIM 5.9. The first return map  $T_{p\eta}^{- }$  satisfies

$$
\left\{ \begin{array}{ll}T_{p\eta}^{-}(s) = \Phi_{p}(s + 1 - \alpha_{p}^{-}(\eta)) = \Phi_{p}(s + \omega_{p}^{+}(\eta)), & \text{if} s< \alpha_{p}^{-}(\eta),\\ T_{p\eta}^{-}(s) = \Phi_{p}(s - \alpha_{p}^{-}(\eta)) = \Phi_{p}(s + \omega_{p}^{+}(\eta) - 1), & \text{if} s > \alpha_{p}^{-}(\eta). \end{array} \right.
$$

Proof. As depicted in Figure 2, there is a segment which projects canonically twice on  $[- 1,\infty ,1]$  and once on  $[- 1,1]$ , so that  $X_{p}^{+}$ ,  $X_{p}^{- 1}$  and  $X_{p\eta}$  define a smooth vector field on it. The image of  $\alpha_{p}(\eta)$  and  $- 1$  by the time  $N$  of its flow are  $1$  and  $\omega_{p}(\eta)$ , respectively. Hence, the time needed to go from  $\alpha_{p}(\eta)$  to  $- 1$  equals the time needed to go from  $1$  to  $\omega_{p}(\eta)$ . This means that

$$
1 - \alpha_{p}^{-}(\eta) = \omega_{p}^{+}(\eta).
$$

If  $s > \alpha_{p}^{- }(\eta)$ , then the first return of  $x = C_{p}^{- }(s)$  in  $[1,\infty , - 1]$  is the image by the flow  $X_{p}^{+}$  of  $1$  after a time  $s - \alpha_{p}^{- }(\eta)$ . In the coordinate  $C_{p}^{+}$ , it is  $s - \alpha_{p}^{- }(\eta)$ . In the coordinate  $C_{p}^{- }$ , it is  $\Phi_{p}(s - \alpha_{p}^{- }(\eta))$ .

If  $s< \alpha_{p}^{- }(\eta)$ , then the first return of  $x = C_{p}^{- }(s)$  in  $[1,\infty , - 1]$  is the image by the flow  $X_{p}^{+}$  of  $\omega_{p}(\eta)$  after a time  $s$ . In the coordinate  $C_{p}^{+}$ , it is  $\omega_{p}^{+}(\eta) + s$ . In the coordinate  $C_{p}^{- }$ , it is  $\Phi_{p}(\omega_{p}^{+}(\eta) + s)$ .

CLAIM 5.10. After gluing the endpoints of  $[0,1]$  by the translation by 1, the map  $T_{p\eta}^{- }$  is a smooth map of the circle  $\mathbb{R} / \mathbb{Z}$ , and the family  $(T_{p\eta}^{- })_{p,\eta}$  is of class  $C^{\infty}$ .

Proof. It is classical [40] that the first return map  $g_{p\eta}$  into  $[1,\infty ,g_{p\eta}(1)] = [1,\infty , - 1]$  is projected to a smooth map of the circle obtained by gluing the endpoints of  $[1,\infty ,g_{p\eta}(1)]$  using  $g_{\eta a}$ . Seen in the chart  $C_p^{- }$ , this corresponds to glue the endpoints of  $[0,1]$  using the translation by  $+1$ . In this specific parabolic context, this map was called "the essential map" in [34].  $\square$

With the conjugacy  $s\mapsto s + \omega_p^+ (\eta)$  and by Claim 5.9, we obtain the following.

COROLLARY 5.11. The first return map  $T_{p\eta}$  of  $g_{p\eta}$  is smoothly conjugated to

$$
R_{p\eta}\colon s\in \mathbb{R} / \mathbb{Z}\longmapsto \Phi_{p}(s) + \omega_{p}^{+}(\eta)\in \mathbb{R} / \mathbb{Z}
$$

Step 3. We shall study the derivative of  $\omega_{p}^{+}(\eta)$  mod 1 with respect to  $\eta$  when  $\eta \to 0$ . We recall that the time needed for the flow  $X_{p\eta}$  to go from  $- 1$  to  $1$  is

$$
\tau_{p}(\eta)\coloneqq \int_{[-1,1]}\frac{1}{X_{p\eta}} d\mathrm{Leb}.
$$

We notice that  $\omega_{p}^{+}(\eta) + \tau_{p}(\eta) = \nabla \in \mathbb{Z}$ , and so

$$
\omega_{p}^{+}(\eta) = -\tau_{p}(\eta)\mod 1.
$$

By Claim 5.6, there exists  $X_{p,\eta}^{1}\in C^{\infty}([- 1,1],\mathbb{R})$  such that

$$
X_{p,\eta}(x) = x^{2}X_{p,\eta}^{1}(x) + \eta^{2}.
$$

As  $g_{p}$  has a unique fixed point at zero, the field  $X_{p0}^{1}$  is positive on  $[- 1,1]$ , with value 1 at zero by Claim 5.6. Thus, for  $\eta$  small, there exists  $C > 0$  such that

$$
X_{p,\eta}^{1}(0) = 1\quad \mathrm{and}\quad X_{p,\eta}^{1}\geqslant C > 0. \tag{5.1}
$$

In this notation, we have

$$
\eta \cdot \tau_{p}(\eta) = \int_{[-1,1]}\frac{\eta}{s^{2}\cdot X_{p\eta}^{1}(s) + \eta^{2}} ds.
$$

We put  $s = \eta \cdot t$  and we have

$$
\eta \cdot \tau_{p}(\eta) = \int_{-1 / \eta}^{1 / \eta}\frac{1}{1 + t^{2}X_{p\eta}^{1}(\eta t)} dt,\quad \mathrm{for~all~}\eta \neq 0.
$$

Let  $\Psi (t,p,\eta)\coloneqq 1 + t^{2}X_{p\eta}^{1}(\eta t)$ .

LEMMA 5.12. For every  $n\geqslant 0$ , there exists  $C_n > 0$  such that, for every  $p\in B'$  and  $\eta$  small,

$$
\left|\partial_{p\eta}^{n}\frac{1}{\Psi(t,p,\eta)}\right|\leqslant \frac{C_{n}}{1 + t^{2}}.
$$

Proof. The case  $n = 0$  is an immediate consequence of inequality (5.1). Let  $n \geq 0$  and assume by induction that Lemma 5.12 holds for every  $k \leq n$ . By Leibniz formula applied to  $\Psi /\Psi$ , we have

$$
\sum_{k = 0}^{n + 1} C_{n + 1}^{k} \frac{\partial^{k} \eta}{\Psi(t, p, \eta)} \cdot \frac{1}{\partial_{p\eta}^{n + 1 - k}} \Psi (t, p, \eta) = 0,
$$

which implies

$$
\frac{1}{\Psi(t, p, \eta)} = -\frac{1}{\Psi(t, p, \eta)} \sum_{k = 0}^{n} C_{n + 1}^{k} \frac{\partial^{k} \eta}{\Psi(t, p, \eta)} \cdot \frac{1}{\partial_{p\eta}^{n + 1 - k}} \Psi (t, p, \eta).
$$

It is easy to see that, for  $0 \leqslant k \leqslant n$ , the derivative  $\frac{\partial^{n + 1 - k} \Psi(t, p, \eta)}{\partial_{p\eta}^{n + 1 - k}}$  is bounded by a certain  $C' \cdot t^{2}$ . Hence, the induction hypothesis gives

$$
\left| \frac{\partial_{p\eta}^{n + 1}}{\Psi(t, p, \eta)} \right| \leqslant \frac{C_{0}}{1 + t^{2}} \sum_{k = 0}^{n} C' \cdot t^{2} \cdot \frac{C_{k}}{1 + t^{2}}
$$

Hence, the above sum is bounded from above by  $C_{n + 1} / (1 + t^{2})$ , for  $C_{n + 1} \in \mathbb{R}$  independent of  $t$ ,  $p \in B$  and  $\eta$  small.

We notice that, by the dominated function theorem, the function

$$
(p, \eta) \longmapsto \eta \cdot \tau_{p}(\eta)
$$

is of class  $C^{\infty}$ . Moreover, we have

$$
\lim_{\eta \to 0} \eta \cdot \tau_{p}(\eta) = \int_{\mathbb{R}} \frac{1}{\Psi(t, p, 0)} dt = \int_{\mathbb{R}} \frac{1}{1 + t^{2}} dt = \pi .
$$

Consequently, the following holds.

FACT 5.13. There exists a  $C^{\infty}$ - family  $(\Omega_{p})_{p}$  of  $C^{\infty}$ - functions  $\Omega_{p} \in C^{\infty}([0, \infty), \mathbb{R})$  such that

$$
\omega_{p}^{+}(\eta) = \frac{\Omega_{p}(\eta)}{\eta} \mod 1.
$$

Proof. Indeed, from the above discussion, the number  $\Omega_{p}(\eta) \coloneqq - \eta \cdot \tau_{p}(\eta)$  depends smoothly on  $p \in \mathbb{R}$  and  $\eta \geq 0$ .

Step 4. We recall that the coordinates change  $\Phi_{p}$  projects to a  $C^{\infty}$ - diffeomorphism of the torus  $\mathbb{R} / \mathbb{Z}$ , and  $(\Phi_{p})_{p}$  is of class  $C^{\infty}$ . Here is an immediate consequence of Herman- Yoccoz' Theorem 5.1.

COROLLARY 5.14. For every Diophantine number  $\beta$ , there exists a  $C^{\infty}$ - function  $p \in B \mapsto \theta (p)$  such that the map  $s \mapsto \Phi_{p}(s) + \theta (p) \in \mathbb{R} / \mathbb{Z}$  has rotation number equal to  $\beta$ .

Hence it remains to solve implicitly:

$$
\omega_{p}^{+}(\eta (p)) = \theta (p)\bmod 1\iff \frac{\Omega_{p}(\eta(p))}{\eta(p)} = \theta (p)\bmod 1.
$$

As  $\Omega_{p}(0) = \pi$ , for every  $p_0\in B$  there exists  $\eta (p_0)$  arbitrarily small such that

$$
\frac{\Omega_{p}(\eta(p_{0}))}{\eta(p_{0})} = \theta (p_{0})\mod 1.
$$

Note that the following derivative is large for  $\eta$  small (since  $\Omega_{p}(0) = \pi$  and  $\partial_{\eta}\Omega_{p}(0)$  is bounded):

$$
\partial_{\eta}\left(\frac{\Omega(\eta)}{\eta}\right) = \frac{\eta\cdot\partial_{\eta}\Omega_{p}(\eta) - \Omega_{p}(\eta)}{\eta^{2}}\sim -\frac{\pi}{\eta^{2}}.
$$

Hence, the implicit function theorem enables us to conclude that, for every  $B^{\prime}\Subset B$  there exists a small smooth function  $p\in B^{\prime}\mapsto \eta (p)$  such that  $R_{p\eta (p)}$  has rotation number equal to  $\beta$ . Then,  $g_{p\eta (p)}$  has a rotation number of the form

$$
\frac{1}{N + \beta},
$$

which is Diophantine as well. Note that  $(g_{p\eta (p)})_{p\in B^{\prime}}$  is  $C^{\infty}$ - close to  $(g_{p})_{p\in B^{\prime}}$ . Thus, Theorem 1.4 is proved.  $\square$

# Appendix A. Extrinsic definition of  $(\lambda)$ -blender and  $C^r$ - $(\lambda)$ -parablender

Let us give for the first time the extrinsic definition of the  $\lambda$ - blender,  $C^r$ - parablender and  $\lambda$ -  $C^r$ - parablender in the diffeomorphism case. The endomorphisms cases of these objects (but not their  $\lambda$ - version) were extrinsically defined in [8], [11].

Let  $f$  be a diffeomorphism of a manifold  $M$  and let  $K$  be a hyperbolic basic set. We assume that  $K$  is partially hyperbolic with a contracting central direction: there exists a  $Df$ - invariant splitting  $TM|_{K} = E^{ss}\oplus E^{c}\oplus E^{u}$  such that, for every  $x\in K$

$$
\| D_{x}f|_{E^{ss}}\| < \| (D_{x}f|_{E^{c}})^{-1}\|^{-1}\leqslant \| (D_{x}f|_{E^{c}})\| < 1\leqslant \| (D_{x}f|_{E^{u}})^{-1}\|^{-1}
$$

We fix a continuous family of strong stable and unstable manifolds  $(W_{\mathrm{loc}}^{ss}(x;f))_{x\in K}$  and  $(W_{\mathrm{loc}}^{u}(x;f))_{x\in K}$ . The lamination  $W_{\mathrm{loc}}^{u}(K;f)\coloneqq \bigcup_{x\in K}W_{\mathrm{loc}}^{u}(x;f)$  is invariant by  $f^{- 1}$ , and so is its tangent bundle. So, for every  $y\in W_{\mathrm{loc}}^{u}(K;f)$  with  $y_{- n}\coloneqq f^{- n}(y)$ , we can consider the action  $[D_{y - n}f^{n}]$  of  $D_{y - n}f^{n}$  on the quotient vector spaces  $T_{y - n}M / T_{y - n}W_{\mathrm{loc}}^{u}(K;f)$  onto  $T_{y}M / T_{y}W_{\mathrm{loc}}^{u}(K;f)$ .

Definition A.1. (( $\lambda$ )- Blender) The hyperbolic compact set  $K$  is a blender if there is  $C^{1}$ - neighborhood  $V^{ss}$  of a strong local stable manifold of  $K$  such that, for every  $C^{1}$ - perturbation  $\tilde{f}$  of  $f$  and every  $W \in V^{ss}$ , there exists  $x \in K$  such that  $W$  intersects  $W_{\mathrm{loc}}^{u}(x; \tilde{f})$ .

The blender  $K$  is a  $\lambda$ - blender if moreover  $\dim E^{c} = 1$  and there exists a non- empty open subset  $U^{\lambda} \subset \mathbb{R}$  such that, for every  $C^{1}$ - perturbation  $\tilde{f}$  of  $f$  and every  $W \in V^{ss}$  and  $\ell \in U^{\lambda}$ , there exists  $x \in K$  such that  $W$  intersects  $W_{\mathrm{loc}}^{u}(x; \tilde{f})$  at a point  $y$  and we have

$$
\lim_{n\to \infty}\frac{1}{n}\log \| [D_{y^{-n}}\tilde{f}^{n}]\| = \ell ,\quad \mathrm{with~}y^{-n}\coloneqq \tilde{f}^{-n}(y).
$$

Let us now give the parametric version of these definitions. Assume that  $(f_{p})_{p \in B_{k}}$  is a  $C^{r}$ - family such that  $f_{0} = f$  and assume that the hyperbolic continuation  $K_{p}$  of  $K = K_{0}$  is well defined for every  $p \in B_{k}$ . Given  $x_{0} \in K_{0}$ , we denote by  $x_{p} \in K_{p}$  its continuation for  $p \in B_{k}$ .

Definition A.2. (( $\lambda$ )-  $C^{r}$ - Parablender) The continuation  $(K_{p})_{p \in B_{k}}$  is a  $C^{r}$ - parablender at  $p_{0} \in B_{k}$  if there is a  $C^{r}$ - neighborhood  $\hat{V}^{ss}$  of the continuation  $(W_{\mathrm{loc}}^{ss}(z_{p}; f_{p}))_{p}$  of a local strong stable manifold of a point  $z_{0} \in K_{0}$  such that the following condition is satisfied. For every  $(\tilde{f}_{p})_{p} C^{r}$ - close to  $(f_{p})_{p}$  and every  $(W_{p})_{p} \in \hat{V}^{ss}$ , there exist a continuation  $(W_{\mathrm{loc}}^{u}(x_{p}; f_{p}))_{p}$  of a local unstable manifold of a point  $z_{0} \in K_{0}$  and  $C^{r}$ - families of points  $(P_{p})_{p}$  in  $(W_{p})_{p}$  and  $(Q_{p})_{p}$  in  $(W_{\mathrm{loc}}^{u}(x_{p}; \tilde{f}_{p}))_{p}$  such that

$$
J_{p_{0}}^{r}(Q_{p})_{p} = J_{p_{0}}^{r}(P_{p})_{p}.
$$

This continuation  $(K_{p})_{p \in B_{k}}$  is a  $\lambda$ -  $C^{r}$ - parablender at  $p_{0}$  if moreover  $\dim E^{c} = 1$  and there exists a non- empty open subset  $J_{p_{0}}^{r} U^{\lambda} \subset J_{p_{0}}^{r - 1} \mathbb{R}$  such that, for every  $(\tilde{f}_{p})_{p} C^{r}$ - close to  $(f_{p})_{p}$  and any  $(W_{p})_{p} \in \hat{V}^{ss}$  and  $\ell \in J_{p_{0}}^{r} U^{\lambda}$ , there exist a continuation  $(W_{\mathrm{loc}}^{u}(x_{p}; f_{p}))_{p}$  of a local unstable manifold of a point  $z_{0} \in K_{0}$  and  $C^{r}$ - families  $(P_{p})_{p}$  in  $(W_{p})_{p}$  and  $(Q_{p})_{p}$  in  $(W_{\mathrm{loc}}^{u}(x_{p}; \tilde{f}_{p}))_{p}$  such that

$$
J_{p_{0}}^{r}(Q_{p})_{p} = J_{p_{0}}^{r}(P_{p})_{p}\quad \mathrm{and}\quad \lim_{n\to \infty}J^{r - 1}\frac{1}{n}\log \| [D_{y_{p}^{-n}}\tilde{f}_{p}^{n}]\| = \ell ,\mathrm{with}y_{p}^{-n}\coloneqq \tilde{f}_{p}^{-n}(y_{p}^{-n})
$$

# References

[1] ARNOLD, V. I., Arnold's Problems. Springer, Berlin; Phasis, Moscow, 2004.

[2] ARTIN, M. & MAZUR, B., On periodic points. Ann. of Math., 81 (1965), 82- 99.

[3] ASAOKA, M., Abundance of fast growth of the number of periodic points in 2- dimensional area- preserving dynamics. Comm. Math. Phys., 356 (2017), 1- 17.

[4] ASAOKA, M., SHINOHARA, K. & TURAEV, D., Degenerate behavior in non- hyperbolic semigroup actions on the interval: fast growth of periodic points and universal dynamics. Math. Ann., 368 (2017), 1277- 1309.

[5] AVILA, A., Distortion elements in Diff  $\infty$  (R/Z). Preprint, 2008. arXiv:0808.2334 [math.DS].

[6] Bencs, F., Buys, P., GuERINI, L. & PeTers, H., Lee- Yang zeros of the antiferromagnetic Ising model. Preprint, 2019. arXiv:1907.07479 [math.DS].

[7] BERGER, P., Persistence of laminations. Bull. Braz. Math. Soc., 41 (2010), 259- 319.

[8] - Generic family with robustly infinitely many sinks. Invent. Math., 205 (2016), 121- 172. Correction in Invent. Math., 218 (2019), 649- 656.

[9] - Emergence and non- typicality of the finiteness of the attractors in many topologies. Proc. Steklov Inst. Math., 297 (2017), 1- 27.

[10] - Complexities of differentiable dynamical systems. J. Math. Phys., 61 (2020), 032702, 12 pp.

[11] BERGER, P., CROVISIER, S. & PUJALS, E., Iterated functions systems, blenders, and parablenders, in Recent Developments in Fractals and Related Fields, Trends Math., pp. 57- 70. Birkhauser/Springer, Cham, 2017.

[12] Bonatti, C. & Diaz, L.J., Persistent nonhyperbolic transitive diffeomorphisms. Ann. of Math., 143 (1996), 357- 396.

[13] Bonatti, C., Diaz, L.J. & Fisher, T., Super- exponential growth of the number of periodic orbits inside homoclinic classes. Discrete Contin. Dyn. Syst., 20 (2008), 589- 604.

[14] Bost, J.- B., Tores invariants des systemes dynamiques hamiltoniens (d'apres Kolmogorov, Arnol'd, Moser, Russmann, Zehnder, Herman, Poschel, ...). Asterisque, 133- 134 (1986), 113- 157, Seminar Bourbaki, Vol. 1984/85.

[15] Bowen, R., On Axiom A Diffeomorphisms. Regional Conference Series in Mathematics, 35. Amer. Math. Soc., Providence, RI, 1978.

[16] CALEGARI, D. & FREEDMAN, M.H., Distortion in transformation groups. Geom. Topol., 10 (2006), 267- 293.

[17] Corwin, L.J. & GREENLEAF, F.P., Representations of Nilpotent Lie Groups and their Applications. Part I. Cambridge Studies in Advanced Mathematics, 18. Cambridge Univ. Press, Cambridge, 1990.

[18] DINH, T.- C., NGUYEN, V.- A. & TRUONG, T. T., Growth of the number of periodic points for meromorphic maps. Bull. Lond. Math. Soc., 49 (2017), 947- 964.

[19] GELFREICH, V. & TURAEV, D., Universal dynamics in a neighborhood of a generic elliptic periodic point. Regul. Chaotic Dyn., 15 (2010), 159- 164.

[20] GORODETSKI, A., HUNT, B. & KALOSHIN, V. Yu., Newton interpolation polynomials, discretization method, and certain prevalent properties in dynamical systems, in International Congress of Mathematicians. Vol. III, pp. 27- 55. Eur. Math. Soc., Zurich, 2006.

[21] HERMAN, M.R., Sur la conjugaison differentiable des diffeomorphismes du cercle a des rotations. Inst. Hautes Etudes Sci. Publ. Math., 49 (1979), 5- 233.

[22] HIRSCH, M.W., PUGH, C.C. & SHUB, M., Invariant Manifolds. Lecture Notes in Mathematics, 583. Springer, Berlin- New York, 1977.

[23] HORMANDER, L., The Analysis of Linear Partial Differential Operators. I. Grundlehren der Mathematischen Wissenschaften, 256. Springer- Verlag, Berlin, 1990.

[24] HUNT, B.R. & KALOSHIN, V. Yu., Prevalence, in Handbook of Dynamical Systems. Chapter 2, pp. 43- 87. 2010.

[25] HUNT, B.R., SAUER, T. & YORKE, J.A., Prevalence: a translation- invariant "almost every" on infinite- dimensional spaces. Bull. Amer. Math. Soc., 27 (1992), 217- 238. Addendum in Bull. Amer. Math. Soc., 28 (1993), 306- 307.

[26] Ilyashenko, Yu. & Li, W., Nonlocal Bifurcations. Mathematical Surveys and Monographs, 66. Amer. Math. Soc., Providence, RI, 1999.

[27] Kaloshin, V. Yu., An extension of the Artin- Mazur theorem. Ann. of Math., 150 (1999), 729- 741.

[28] — Generic diffeomorphisms with superexponential growth of number of periodic orbits. Comm. Math. Phys., 211 (2000), 253- 271.

[29] Kaloshin, V. Yu. & Hunt, B. R., A stretched exponential bound on the rate of growth of the number of periodic points for prevalent diffeomorphisms II. Electron. Res. Announc. Amer. Math. Soc., 7 (2001), 28- 36.

[30] — Stretched exponential estimates on growth of the number of periodic points for prevalent diffeomorphisms. I. Ann. of Math., 165 (2007), 89- 170.

[31] Kaloshin, V. Yu. & Saprykina, M., Generic 3- dimensional volume- preserving diffeomorphisms with superexponential growth of number of periodic orbits. Discrete Contin. Dyn. Syst., 15 (2006), 611- 640.

[32] Martens, M., de Melo, W. & van Strien, S., Julia- Fatou- Sullivan theory for real one- dimensional dynamics. Acta Math., 168 (1992), 273- 318.

[33] Rodriguez Hertz, F., Rodriguez Hertz, M. A. & Ures, R., A survey of partially hyperbolic dynamics, in Partially Hyperbolic Dynamics, Laminations, and Teichmüller Flow, Fields Inst. Commun., 51, pp. 35- 87. Amer. Math. Soc., Providence, RI, 2007.

[34] Shilnikov, L. P. & Turayev, D. V., A new simple bifurcation of a periodic orbit of "blue sky catastrophe" type, in Methods of Qualitative Theory of Differential Equations and Related Topics, Amer. Math. Soc. Transl. Ser. 2, 200, pp. 165- 188. Amer. Math. Soc., Providence, RI, 2000.

[35] Smale, S., Differentiable dynamical systems. Bull. Amer. Math. Soc., 73 (1967), 747- 817.  [36] Sternberg, S., Local  $C^n$  transformations of the real line. Duke Math. J., 24 (1957), 97- 102.

[37] Turayev, D., Polynomial approximations of symplectic dynamics and richness of chaos in non- hyperbolic area- preserving maps. Nonlinearity, 16 (2003), 123- 135.

[38] Maps close to identity and universal maps in the Newhouse domain. Comm. Math. Phys., 335 (2015), 1235- 1277.

[39] Yoccoz, J.- C., Conjugaison differentiable des diffeomorphismes du cercle dont le nombre de rotation verifie une condition diophantienne. Ann. Sci. École Norm. Sup., 17 (1984), 333- 359.

[40] Centralisateurs et conjugaison differentiable des diffeomorphismes du cercle. Astérisque, 231 (1995), 89- 242, Petits diviseurs en dimension 1.

PIERRE BERGER

CNRS- Institut Mathématique

de Jussieu Paris Rive Gauche

Université Sorbonne, UMR 7586

4 place Jussieu - Boite Courrier 247

FR- 75252 Paris

France

pierre.berger@imj- prg.fr

Received January 9, 2017

Received in revised form April 15, 2020