FROM dynaum/node-sqlite

RUN cd / \
	&& git clone https://github.com/fabianekc/fitbit_dumper.git \
	&& cd /fitbit_dumper \
	&& npm install -g fitbit_dumper

CMD ["/bin/bash"]
