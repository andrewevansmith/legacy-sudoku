import os

build_directory = os.path.join(os.getcwd(), 'build', 'scipy2010')

env = Environment(ENV=os.environ)
env['PDFLATEXFLAGS'] = ['-interaction=nonstopmode', '-recorder', '--shell-escape']

Export('env')
SConscript(['SConscript'],build_dir=build_directory)
