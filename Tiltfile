
EXTENSIONS_DIR = os.path.abspath("./custom_repo")

v1alpha1.extension_repo(name='custom_repo', url="file:///%s" % EXTENSIONS_DIR)
v1alpha1.extension(name='my_ext_1', repo_name='custom_repo', repo_path='my_ext_1')
v1alpha1.extension(name='my_ext_2', repo_name='custom_repo', repo_path='my_ext_2')

load('ext://my_ext_1', 'setup_repo')

setup_repo()

