
stuff = Background.tex Background_CMB.tex Background_CMB_long.tex Background_Cores.tex Background_Galaxies.tex Background_Turb.tex Geometry.tex Method.tex OtherResources.tex Personnel.tex SimulationPlan.tex Simulations_CMB.tex Simulations_Cores.tex Simulations_Galaxies.tex Simulations_Turb.tex aas_papers.tex commands.tex fig_cores.tex fig_energy.tex fig_planck.tex introduction.tex ms.tex names.tex table1.tex table1_caption.tex table2.tex table2_caption.tex

proposal:  $(stuff)
	pdflatex ms
	pdflatex ms
	bibtex ms
	pdflatex ms

o: $(stuff)
	pdflatex ms


scaling: Scaling.tex
	pdflatex Scaling
	pdflatex Scaling
	bibtex Scaling
	pdflatex Scaling
	pdflatex Scaling

progress: Progress.tex
	pdflatex Progress
	pdflatex Progress
	bibtex Progress
	pdflatex Progress
