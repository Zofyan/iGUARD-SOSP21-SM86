DIRS         ?= ScoR CG Gunrock LS Kilo-TM SHoC CUB Rodinia cuML SlabHash
RUNS         ?= 1
PREFIX_NODET ?= NODET
PREFIX_DET   ?= IGUARD

run:
	for i in ${DIRS}; do \
		cd $$i;      \
		$(MAKE) run RUNS=${RUNS} PREFIX_NODET=${PREFIX_NODET} PREFIX_DET=${PREFIX_DET}; \
		cd ..;       \
	done
