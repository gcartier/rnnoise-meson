rnnoise_inc = ['../include']

rnnoise_sources = [
  'celt_lpc.c',
  'denoise.c',
  'kiss_fft.c',
  'pitch.c',
  'rnn_data.c',
  'rnn.c'
]

rnnoise = library('rnnoise',
  rnnoise_sources,
  include_directories : [rnnoise_inc],
)
