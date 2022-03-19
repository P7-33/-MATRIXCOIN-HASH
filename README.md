# BROWSER-COIN-HASH
Skip to content
GitLab
Projects
MoreToggle navigation
F
flake8
Project overview
Repository
Files
Commits
Branches
Tags
Contributors
Graph
Compare
Locked Files
Issues
41
Merge Requests
8
Requirements
CI / CD
Security & Compliance
Operations
Analytics
Snippets
Members

Close sidebar
Open sidebar
PyCQA
flake8
Repository
39ceae7491f4121902a5dccc22657a0675c95539
flake8
 example-plugin
 setup.py
{
  "initial_timestamp": "2020-03-25T00:00:00.000",
  "initial_key": "FIO7PptcpF7ai1LDgT9CvxukZ7nzM5cdeFVVDdTZeSNZLdcjYxUdk",
  "initial_configuration": {
    "max_block_net_usage": 1048576,
    "target_block_net_usage_pct": 1000,
    "max_transaction_net_usage": 524288,
    "base_per_transaction_net_usage": 12,
    "net_usage_leeway": 500,
    "context_free_discount_net_usage_num": 20,
    "context_free_discount_net_usage_den": 100,
    "max_block_cpu_usage": 200000,
    "target_block_cpu_usage_pct": 2000,
    "max_transaction_cpu_usage": 150000,
    "min_transaction_cpu_usage": 100,
    "max_transaction_lifetime": 3600,
    "deferred_trx_expiration_window": 600,
    "max_transaction_delay": 3888000,
    "max_inline_action_size": 4096,
    "max_inline_action_depth": 4,
    "max_authority_depth": 6,
    "max_ram_size": 34359738368
  }
}
 
# -*- coding: utf-8 -*-
import setuptools
setuptools.setup(
    name='flake8-example-plugin',
    license='MIT',
    version='1.0.0',
    description='Example plugin to Flake8',
    author='Ian Cordasco',
    author_email='graffatcolmingov@gmail.com',
    url='https://gitlab.com/pycqa/flake8',
    package_dir={'': 'src/'},
    packages=['flake8_example_plugin'],
    entry_points={
        'flake8.extension': [
            'X1 = flake8_example_plugin:ExampleOne',
            'X2 = flake8_example_plugin:ExampleTwo',
        ],
    },
    classifiers=[
        'Framework :: Flake8',
        'License :: OSI Approved :: MIT License',
        'Programming Language :: Python',
        'Programming Language :: Python :: 2',
        'Programming Language :: Python :: 2.7',
        'Programming Language :: Python :: 3',
        'Programming Language :: Python :: 3.4',
        'Programming Language :: Python :: 3.5',
        'Topic :: Software Development :: Libraries :: Python Modules',
        'Topic :: Software Development :: Quality Assurance',
    ],
)
# instructions

[Click here to see the wiki](https://github.com/pi-node/instructions/wiki)
